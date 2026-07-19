# Flask Registration Form

A simple **Flask web application** that allows users to enter their details through a registration form and displays the submitted information on a confirmation page.

---

## 📌 Features

* User registration form
* Accepts user input:

  * Name
  * City
  * Phone Number
* Displays the submitted information on a confirmation page
* Built using the Flask web framework
* Uses HTML templates for the user interface

---

## 📂 Project Structure

```text
Flask-Registration/
│
├── app.py
├── templates/
│   ├── register.html
│   └── confirm.html
├── static/          (Optional)
└── README.md
```

---

## 🛠️ Technologies Used

* Python 3.x
* Flask
* HTML5

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/sohelahmedangadi/Flask-Registration.git
```

### 2. Navigate to the project directory

```bash
cd Flask-Registration
```

### 3. Create a virtual environment (Optional)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install Flask

```bash
pip install flask
```

---

## ▶️ Running the Application

Run the Flask application:

```bash
python app.py
```

The application will start in development mode.

Open your browser and visit:

```text
http://127.0.0.1:5000/
```

---

## 📋 Registration Form

The application collects the following information:

* Name
* City
* Phone Number

After submitting the form, the entered details are displayed on a confirmation page.

---

## 📚 Concepts Used

* Flask application setup
* Routing with `@app.route()`
* HTML templates using Jinja2
* Form handling with `request.form`
* HTTP GET and POST methods
* Rendering templates with `render_template()`

---

## 📸 Workflow

1. User opens the registration page.
2. User enters Name, City, and Phone Number.
3. User submits the form.
4. Flask receives the data using the POST method.
5. A confirmation page displays the submitted information.

---

## 🚀 Future Improvements

* Form validation
* Store user data in a database
* Add email field
* Improve UI using Bootstrap
* Display success messages
* Add login and authentication

---

## 👨‍💻 Author

**Sohail Ahmed**

GitHub: https://github.com/sohelahmedangadi
