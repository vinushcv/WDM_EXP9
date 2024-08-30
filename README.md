### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:

![image](https://github.com/user-attachments/assets/76f2e904-69c0-41b7-9b5f-70d816e57605)

![image](https://github.com/user-attachments/assets/8c4f70e7-71a3-436d-a6bf-cb6c6ead0add)


![image](https://github.com/user-attachments/assets/24a851ab-633b-4c66-a09d-034a1e5fb56a)

![image](https://github.com/user-attachments/assets/dc71afbd-25b3-42a2-aef3-5357376cfc00)

### Select:
![image](https://github.com/user-attachments/assets/cc556b55-4381-4b4f-acfa-2cd537f8f25a)

### Replace:
![image](https://github.com/user-attachments/assets/4b51d8eb-34b9-476e-8acf-f65c8ccc0ba2)

### Tokenize:
![image](https://github.com/user-attachments/assets/cdcc2eaf-f7b9-4b04-91f1-11af38e64be2)

### Transform Cases:
![image](https://github.com/user-attachments/assets/f12d77f5-869e-4e8b-989f-b9574a09e90d)

### Filter Tokens:
![image](https://github.com/user-attachments/assets/2722c595-cf7a-4893-9200-bac25880ffd7)

### Filter Stopwords:
![image](https://github.com/user-attachments/assets/1dc78e06-33b4-48c9-9607-7941e577f319)

### Stem:


![image](https://github.com/user-attachments/assets/baa93327-55af-4ab6-ad30-a3f02a0f0b03)


### Result:
Thus the implementation of preprocessing technique on Twitter Data using Rapidminer is executed successfully.
