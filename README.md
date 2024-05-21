### Wiki Encyclopedia Project 1

### Overview
This project is a simple Wiki encyclopedia web application built using Django. It allows users to view, create, edit, and search for encyclopedia entries. Each entry is stored as a markdown file and is dynamically rendered into HTML for display.

### Features
Entry Page: Display the contents of an encyclopedia entry.
Index Page: List all encyclopedia entries with links to each entry.
Search: Search for entries by title or content substring.
New Page: Create new encyclopedia entries.
Edit Page: Edit existing encyclopedia entries.
Random Page: View a random encyclopedia entry.
Markdown to HTML Conversion: Convert markdown content to HTML for display.

### Requirements
Python 3.x

Django 3.x

markdown2 (optional, for Markdown to HTML conversion)

### Watch on YouTube
[Click link to Watch the video](https://youtu.be/xgvJ38fQp4k?si=kTbi3pXh-L2wMbdc)

## Installation
To set up this project on your computer:

1. **Download this project**
   ```sh
   git clone https://github.com/suman154/Wiki.git
2. Install all necessary dependencies
   ```sh
   pip install -r requirements.txt
3. Make migrations
   ```sh
   python manage.py makemigrations
4. Migrate
   ```sh
   python manage.py migrate
5. Run the server
   ```sh
   python manage.py runserver

  ### Running Tests
  To run the tests, use Django's test framework:
  ```sh
  python manage.py test
  ```

  ### Deployment
  To deploy this project, you will need to configure a web server (e.g., Apache or Nginx) and a production database. Ensure you set the appropriate settings in settings.py for         
  deployment, including DEBUG = False and proper configuration of ALLOWED_HOSTS, database settings, and static file handling.

  ### Contributing
  Contributions are welcome! Please submit a pull request or open an issue to discuss any changes or improvements.

  ### Acknowledgements
  The project uses markdown2 for Markdown to HTML conversion.
  Built with Django framework.

  
