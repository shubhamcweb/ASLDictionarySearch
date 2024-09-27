# ASL Search

## Description
ASL Search is a computer vision project aimed at recognizing signs in American Sign Language (ASL) using pattern recognition techniques. This project was developed and presented at the OurCS@DFW UTA Student Computing Research Festival 2023.

The system uses nearest neighbor classification on ASL datasets provided by Dr. Vassilis Athitsos' research to identify and interpret ASL signs. By leveraging Python and Google Colab, this project demonstrates the potential of machine learning in bridging communication gaps for the deaf and hard-of-hearing community.

## Features
- Recognizes ASL signs using computer vision techniques
- Implements nearest neighbor classification for pattern recognition
- Utilizes ASL datasets from Dr. Vassilis Athitsos' research
- Developed and run in Google Colab for easy accessibility and collaboration

## Technologies Used
- Python
- Google Colab
- NumPy
- SciPy
- Matplotlib

## Installation
As this project is developed in Google Colab, no local installation is required.

## Usage
1. Run the cells in the notebook sequentially.
2. The notebook includes functions for:
   - Loading and processing ASL sign data
   - Standardizing sign representations
   - Implementing nearest neighbor classification
   - Evaluating accuracy of the classification

3. Key functions include:
   - `load_annotations()` and `load_handface()` for loading dataset information
   - `standardize3()` for normalizing sign data
   - `make_set3()` for creating standardized datasets
   - `compute_dist3()` for computing distances between signs
   - `topk_accuracy()` for evaluating the model's accuracy

4. The notebook demonstrates the improvement of the model through different iterations, with the final version using both dominant and non-dominant hand data.

5. You can modify the `fixed_size` variable to adjust the number of frames used in the standardized representation of signs.

6. The final accuracy of the model is printed at the end of the notebook.

## Contributors
- Shubham Chandravanshi
- Dr. Vassilis Athitsos

## Acknowledgments
- Dr. Vassilis Athitsos, Professor of Computer Science and Engineering at The University of Texas at Arlington, for providing the ASL datasets and research guidance.
  - Email: athitsos@uta.edu
  - Research Interests: Computer Vision, Machine Learning, Data Mining, Gesture and Sign Language Recognition, Face Recognition
- OurCS@DFW UTA Student Computing Research Festival 2023 organizers and mentors.

## License
MIT License

Copyright (c) 2024 Shubham Chandravanshi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.