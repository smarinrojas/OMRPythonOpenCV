# Detection of Marks on Answer Sheets with OMR (Optical mark recognition)

This project uses computer vision techniques and Optical Mark Recognition (OMR) to detect and process marks on scanned answer sheets. The goal is to automate the evaluation of exams or questionnaires by identifying the options chosen by students.

Process
*Corner Detection*: Template matching is used to identify the corners of the answer sheet in the scanned image. This allows for correcting the perspective and aligning the image for precise processing.

*Perspective Transformation*: A perspective transformation is applied to correct any image distortion and obtain a front view of the answer sheet.

*Mark Detection*: The transformed image is scanned to detect the presence of marks in the designated areas for answers.

*Response Interpretation*: The position of the detected marks is analyzed to determine the option chosen by the student for each question.