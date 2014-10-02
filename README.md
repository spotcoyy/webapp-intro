webapp-intro
============

This will be a repo to host a basic Flask application for class.

Example
============

```python
from flask import Flask
app = Flask(__name__)

@app.route("/")
def hello():
    return "Hello World!"

if __name__ == "__main__":
    app.run()
```

Blog/Tutorial
============

http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world

Sharing Your Work
===========
1) Once in Cloud9, create a new file named (yourname).py.
![Create a new file.](http://cl.ly/image/0q161Z3f2K3h/Screen%20Shot%202014-10-01%20at%208.26.18%20PM.png)

2) Use the terminal to add your file to the repository.
- `git add (yourname.py)`
- `git commit -m "(Commit Message)"`
- `git push origin master`
- ![Add, Commit, Push](http://cl.ly/image/0m2H373m1j2h/Screen%20Shot%202014-10-01%20at%208.28.01%20PM.png)

3) Create a pull request from your fork to the IntroToPython/objects-101 repo.
- At the main screen for your fork, click the large green button with arrows on it next to the branch name.
- Click the large Create Pull Request button and name your pull request.
- Click Create Pull Request one more time.
![Creating a PR](http://cl.ly/image/1i232B3L1R0c/Screen%20Shot%202014-10-01%20at%208.29.14%20PM.png)

This process will allow peer review on any incoming work, along with the ability to discuss specific lines on the same page.

Questions?
============
anthony@blar.do
