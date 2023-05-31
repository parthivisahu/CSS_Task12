# CSS_Task12
README for Simple Registration Form with Avatar
-----------------------------------------------

This README provides instructions on how to create a simple registration form with an avatar using HTML and CSS. By following these steps, you can create a basic form where users can input their information, including an avatar image. Here's how to get started:

1. HTML Structure:
   - Begin by creating a new HTML file using a text editor or an Integrated Development Environment (IDE).
   - Inside the `<body>` element, create a `<form>` element to encapsulate the registration form.
   - Within the form, add various input fields such as `<input type="text">`, `<input type="email">`, `<input type="password">`, etc., for users to enter their information.
   - Include a file input field (`<input type="file">`) to allow users to upload their avatar image.
   - Add a submit button (`<input type="submit">`) to allow users to submit the form.

2. CSS Styling:
   - Create a new CSS file or add CSS styles within the `<style>` tag in the `<head>` section of your HTML file.
   - Select the form and its child elements using appropriate CSS selectors and apply desired styling. For example:
     ```css
     form {
       max-width: 400px;
       margin: 0 auto;
     }

     input[type="text"],
     input[type="email"],
     input[type="password"],
     input[type="file"],
     input[type="submit"] {
       margin-bottom: 10px;
       width: 100%;
       padding: 10px;
       border: 1px solid #ccc;
     }

     /* Add additional styles as per your design preferences */
     ```

3. Apply CSS to HTML:
   - In your HTML file, link the CSS file by adding the following line of code within the `<head>` section:
     ```html
     <link rel="stylesheet" href="path/to/your/css-file.css">
     ```
   - Replace `"path/to/your/css-file.css"` with the actual path to your CSS file.

4. Save and Preview:
   - Save both your HTML and CSS files.
   - Open the HTML file in a web browser to see the simple registration form with an avatar.

Congratulations! You have successfully created a simple registration form with an avatar using HTML and CSS. Customize the form further by adding labels, additional input fields, validation, or any other desired features. Enhance the design by adjusting the CSS properties, adding styling to labels and buttons, or incorporating any design elements that match your project's requirements.
