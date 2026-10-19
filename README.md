# My Todo List

A simple and robust To-Do list application built with Python and Flask. This application allows users to register, log in, and manage their personal tasks efficiently.

## Features

- **User Authentication**: Secure registration and login functionality.
- **Task Management**:
  - Add new tasks.
  - View list of tasks.
  - Update task details.
  - Delete individual tasks.
  - Clear all tasks at once.
- **Status Tracking**: Toggle task status through a workflow: `Pending` -> `Working` -> `Done`.
- **Data Persistence**: Uses SQLite database to save your tasks and user data.

## Installation

1.  **Clone the repository** (if you haven't already):
    ```bash
    git clone <repository-url>
    cd My-todo-list
    ```

2.  **Install Dependencies**:
    It is recommended to use a virtual environment.
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  **Run the Application**:
    ```bash
    python run.py
    ```

2.  **Access the App**:
    Open your web browser and navigate to.
    `http://127.0.0.1:5000`

3.  **Get Started**:
    - Register a new account.
    - Log in with your credentials.
    - Start adding and managing your tasks!

## Project Structure

- `aap/`: Main application package containing routes, models, templates, and static files.
- `instance/`: Contains the SQLite database (`todo.db`).
- `run.py`: The entry point to run the application.
