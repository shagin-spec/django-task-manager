# Task Manager Web Application

A full-stack task management web application built with Django — featuring user authentication, task creation, deletion, and filtering in a clean, responsive interface.

---

## Features

- **User Authentication** — Secure login and logout system
- **Add Tasks** — Create tasks with title and details
- **Delete Tasks** — Remove completed or unwanted tasks
- **Filter Tasks** — Filter by status to stay organized
- **Responsive UI** — Works across desktop and mobile screen sizes

---

## Tech Stack

| Layer | Technology |
|---|---|
| Backend | Python, Django |
| Frontend | HTML5, CSS3 |
| Database | SQLite, MySQL |
| Testing | Manual Testing |
| Version Control | Git, GitHub |

---

## Getting Started

### Prerequisites
Make sure you have the following installed:
- Python 3.x
- pip
- Git

### Installation

**1. Clone the repository**
```bash
git clone https://github.com/shagin-spec/task-manager.git
cd task-manager
```

**2. Create a virtual environment**
```bash
python -m venv env
source env/bin/activate        # On Windows: env\Scripts\activate
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

**4. Run database migrations**
```bash
python manage.py makemigrations
python manage.py migrate
```

**5. Start the development server**
```bash
python manage.py runserver
```

**6. Open in browser**
```
http://127.0.0.1:8000
```

---

## Project Structure

```
task-manager/
├── manage.py
├── requirements.txt
├── taskmanager/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── tasks/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
│       └── tasks/
│           ├── index.html
│           ├── login.html
│           └── task_list.html
└── static/
    └── css/
        └── style.css
```

---

## Testing

Manual testing was performed across all 4 core modules:

- User login and logout flow
- Task creation with valid and invalid inputs
- Task deletion confirmation
- Filter functionality across task states

---

## Developer

**A. Shagin Banu**  
BSc Information Technology — Dhanalakshmi Srinivasan University  
CGPA: 9.01 | Top 20 of 20,000+ — ICT Youth Talk

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/shagin-banu-banu-1ba2a5398)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:shaginarif@gmail.com)
