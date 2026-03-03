# BMI Calculator 

A sleek, functional **Body Mass Index (BMI) Calculator** built with Vanilla JavaScript. This project provides a simple interface for users to calculate their BMI based on height (cm) and weight (kg).

##  Live Demo
Check out the live application here:  
**[Insert your GitHub Pages link here]**

---

## 🛠️ Features
* **Instant Calculation:** Computes results immediately on click.
* **Metric Support:** Designed for height in centimeters and weight in kilograms.
* **Precision Output:** Results are formatted to two decimal places for clarity.
* **Clean Logic:** Built with optimized, readable JavaScript.

---

##  The Formula
The application uses the standard metric system formula to calculate the score:

$$BMI = \frac{weight (kg)}{[height (m)]^2}$$

In the code, we convert the height from centimeters to meters before calculating:
`let bmi = weight / ((height / 100) * (height / 100));`

---

##  Project Structure
* `index.html` - The UI structure and input fields.
* `style.css` - Custom styling for a modern look.
* `script.js` - The calculation logic and DOM manipulation.

---

##  How to Use
1.  Enter your **height** in centimeters (e.g., 180).
2.  Enter your **weight** in kilograms (e.g., 75).
3.  Click the **Calculate** button.
4.  Your BMI result will appear instantly below the button.

---

## 📝 License
This project is open-source and available under the [MIT License](LICENSE).

---
*Created by [Your Name]*
