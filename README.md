# Social Network Data Analysis and Recommendation System Using Python

## About the Project

This is my Python-based Data Science project. In this project, I worked with social network data stored in JSON files.

The main idea is to understand how users are connected with each other and what pages they are interested in. I used Python to convert JSON data into Python objects, display user connections, clean the data, and suggest new friends and pages based on users' interests.

## What I Did in This Project

**1. JSON to Python Object**
- Loaded JSON files using Python.
- Converted JSON data into Python dictionaries and lists.
- Accessed user and page information.

**2. Show User Connections**
- Displayed users and their friends.
- Showed connections between different users.
- Displayed pages liked by users.

**3. Data Cleaning**
- Removed users with missing names.
- Removed duplicate friend IDs.
- Cleaned unnecessary and duplicate records.
- Saved the cleaned data into a new JSON file.

**4. People Suggestions**
- Found mutual friends between users.
- Suggested new people based on common connections.
- Avoided suggesting people who are already friends.

**5. Page Suggestions**
- Checked users' liked pages.
- Found common interests.
- Suggested new pages based on similar interests.

## Technologies Used

- Python
- JSON
- Jupyter Notebook
- Python Lists, Dictionaries and Sets

## Project Files

```text
Social-Network-Recommendation-System/
│
├── show_connection.ipynb
├── data_cleaning.ipynb
├── susgestion.ipynb
├── pages_suggestion.ipynb
│
├── data4.json
├── data5.json
├── cleaned_data2.json
│
└── README.md
```

## How to Run This Project

1. Download or clone this repository.
2. Install Python on your computer.
3. Install Jupyter Notebook.
4. Open the project folder in Jupyter Notebook.
5. Run the notebooks one by one.

Install Jupyter Notebook:

```bash
pip install notebook
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

## What I Learned

While working on this project, I learned how to:

- Work with JSON files in Python.
- Convert JSON data into Python objects.
- Clean and organize raw data.
- Understand user connections.
- Find mutual friends.
- Build basic people and page recommendation logic.

## Future Improvements

In the future, I would like to improve this project by adding a simple user interface, data visualization, and more advanced recommendation techniques.

## Author

MR.Imran Mulani

BCA Student | Data Science & AI/ML

This project is part of my learning journey in Python and Data Science.
