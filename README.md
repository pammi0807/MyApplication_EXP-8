# MyApplication_EXP-8

Aim
To create an Android-based temperature converter application that performs conversion between Fahrenheit and Celsius scales.
Algorithm


Start Android Studio and create a mobile application project.


Create the layout file using LinearLayout with EditText, Buttons, and TextView components.


Provide an input field for entering temperature values.


Create buttons for converting temperature values and clearing data.


Initialize all widgets inside the onCreate() method.


Use setOnClickListener() for handling button click events.


When the Convert to Fahrenheit button is clicked, read the Celsius input value.


Apply the conversion formula:
F=9C5+32F = \frac{9C}{5} + 32F=59C​+32


Display the Fahrenheit result in the TextView.


When the Convert to Celsius button is clicked, read the Fahrenheit value.


Apply the conversion formula:
C=5(F−32)9C = \frac{5(F-32)}{9}C=95(F−32)​


Show the converted Celsius result on the screen.


Implement the Clear button to reset the EditText and result display.


Handle empty input conditions properly.


Execute the application and test all functionalities successfully.

