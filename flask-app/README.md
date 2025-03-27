# Flask Application

This is a simple Flask application that provides user registration and login functionalities. It uses SQLite as the database and includes basic templates for user interaction.

## Project Structure

```
flask-app
├── app.py                # Main application file
├── templates             # HTML templates
│   ├── base.html        # Base template
│   ├── index.html       # Index page template
│   ├── login.html       # Login page template
│   └── register.html    # Registration page template
├── static               # Static files (CSS and JS)
│   ├── css
│   │   └── styles.css   # CSS styles
│   └── js
│       └── scripts.js    # JavaScript code
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation
```

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/flask-app.git
   cd flask-app
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

4. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:
   ```
   python app.py
   ```

2. Open your web browser and go to `http://127.0.0.1:5000/`.

3. You can register a new user or log in with existing credentials.

## License

This project is licensed under the MIT License - see the LICENSE file for details.