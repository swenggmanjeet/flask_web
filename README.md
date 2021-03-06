## flask_web

The code was released along with the articles published on [Freelancer.com's Community](https://www.freelancer.com/community) webpage:
 - [Web Development using Flask - Part 1](https://www.freelancer.com/community/articles/web-development-using-flask-part-1)
 - [Web Development using Flask - Part 2](https://www.freelancer.com/community/articles/web-development-using-flask-part-2)


Project which presents how flask can be used with foundation and with pymongo for web development.

### Running the app

You can run the app using the `python app.py` command in the `flask_web` directory.

#### Prerequisits

1. MongoDB - the default setting is considered that it is installed locally and running on localhost:27017
2. Python Libraries
  * virtualenv - using the below commands the virtual env can be started and then the libraries can be installed there
    ```bash
    $ virtualenv venv
    $ source venv/bin/activate
    ```

  * without virtualenv
    ```bash
    pip install flask
    pip install pymongo
    ```
