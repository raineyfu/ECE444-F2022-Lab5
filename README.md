This repo is a clone of: https://github.com/nelaturuk/education_pathways

![image](https://user-images.githubusercontent.com/59759137/197931849-3676550c-d834-4c16-985c-8bcf92d826c7.png)


![image](https://user-images.githubusercontent.com/59759137/197935095-44f88079-48b7-424c-bb87-50a731e504ad.png)
Toggle switch for changing between 2 different page styles
![image](https://user-images.githubusercontent.com/59759137/197935641-0fe90342-247c-4b70-879e-77894bcabeab.png)

![image](https://user-images.githubusercontent.com/59759137/197936142-f6f4a198-5580-4dda-b7d9-a197dbe30dca.png)
Aesthetic file upload input to allow users to upload syllabus and other important course content to share
![image](https://user-images.githubusercontent.com/59759137/197936088-25f96fd8-347e-4131-a8a9-8da211b0ad51.png)

![image](https://user-images.githubusercontent.com/59759137/197936632-803472d0-8e5b-4691-8bfa-72d22639e763.png)
Feedback form to allow users to report malicious content or submit suggestions
![image](https://user-images.githubusercontent.com/59759137/197936614-35f2891e-de2d-40c1-83ba-d55b412ce9ae.png)





# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
