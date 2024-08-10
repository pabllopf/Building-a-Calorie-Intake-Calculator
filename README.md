# Building-a-Calorie-Intake-Calculator
Develop a new app feature with your Python skills to calculate calories and nutrition values from user input.


# Project Instructions
Enhance the Diet Coach app by creating the nutritional_summary() function to calculate and return the total nutritional values from the nutrition_dict dataset.

Function Output:

If all the foods are present in the dataset, the function returns a dictionary with keys: "calories", "total_fat", "protein", "carbohydrate", "sugars".

If any food is missing from the dataset, the function returns the name of the first missing item.

Input Format:

Dictionary: For example, calling nutritional_summary({"Croissants, cheese": 150, "Orange juice, raw": 250}) should output {'calories': 733.5, 'total_fat': 32.0, 'protein': 15.55, 'carbohydrate': 96.5, 'sugars': 38.025} Here, 150 and 250 represent the grams of each food.

Handling non-existent keys: For example, calling nutritional_summary({"Croissant": 150, "Orange juice": 250}) should output "Croissant".


![image](https://github.com/user-attachments/assets/7007618c-d377-40ea-98df-e317ca24f442)


As a Software Engineer in a Health and Leisure company, your task is to add a new feature to the app: a calorie and nutrition calculator. This tool will calculate and display total calories, sugars, fats, and other nutritional values for different foods based on user input.

You have been provided with the `nutrition.json` dataset, which contains the necessary nutritional information for various foods. Each value in the dataset is per **100 grams** of the food item. The dataset has already been read and loaded for you as the dictionary `nutrition_dict`.

## Dataset Summary

`nutrition.json`

| Column        | Description                                             |
|---------------|---------------------------------------------------------|
| `food` | The name of the food.                                   |
| `calories`  | The amount of energy provided by the food, measured in kilocalories (kcal) per 100 grams. |
| `total_fat` | The total fat content in grams per 100 grams.                         |
| `protein`   | The protein content in grams per 100 grams.                           |
| `carbohydrate` | The total carbohydrate content in grams per 100 grams.             |
| `sugars`    | The amount of sugars in grams per 100 grams.                          |

### Let's Get Started!

This project is a great opportunity to build a real-world feature from scratch, showcasing your development skills and making a meaningful impact on users' health and wellness.
