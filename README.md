# Computer_vision
The aim of this project is to extract and identify handwriting.

## Data
As far as the data is concerned, we are using only part of the IAM handwriting database, some or all of the 1,539 pages of scanned text. The dataset come from Kaggle: https://www.kaggle.com/datasets/naderabdalghani/iam-handwritten-forms-dataset

## Process
This project will be carried out in several stages:

1. Segmentation of the page to extract the part where the handwriting is located.
  ![bounding_box_animation](https://github.com/vyvern1/Computer_vision/assets/55856046/34a99488-66b0-4b47-bf95-457eae433f4e)
  - Use the MSER algorithm 

2. Segmentation of paragraphs into lines
   ![image](https://github.com/vyvern1/Computer_vision/assets/55856046/7d8ad326-e105-48b7-bb0b-cea1166c4d19)
   - Horizontal Projection Profile (HPP)
   ![image](https://github.com/vyvern1/Computer_vision/assets/55856046/79bc5dc0-0d9f-4411-97bf-9a9d8f569eed)
   - A* algorithm

3. Handwriting recognition
   - TrOCR
     
4. Evaluation
   ![image](https://github.com/vyvern1/Computer_vision/assets/55856046/e0b59739-e7a4-4526-90ca-4d69660a59e3)

## Example
![image](https://github.com/vyvern1/Computer_vision/assets/55856046/07cd88bf-d44f-419c-8bdf-41241ba62e7e)



