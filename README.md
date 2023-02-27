# OpenAI API Quickstart - Python example app

This is simple python ChatGPT app developed using the the OpenAI API [quickstart tutorial](https://beta.openai.com/docs/quickstart). It uses the [Flask](https://flask.palletsprojects.com/en/2.0.x/) web framework. Check out the tutorial or follow the instructions below to get set up.

## Setup

1. If you don’t have Python installed, [install it from here](https://www.python.org/downloads/). If you do have Python installed, ensure it is fully up to date

   ```bash
   $ python.exe -m pip install --upgrade pip
   ```

2. Ensure you have virtualenv installed

   ```bash
   $ pip install virtualenv
   ```

3. Fork/Clone this repository

4. Navigate into the project directory

   ```bash
   $ cd openai-quickstart-python
   ```

5. Create a new virtual environment

   ```bash
   $ python -m venv venv
   $ . venv/bin/activate
   ```
   
   If the above encounters an error, try:
   ```bash
   $ python -m venv venv
   $ . venv/scripts/activate
   ```

6. Install the requirements

   ```bash
   $ pip install -r requirements.txt
   ```

7. Make a copy of the example environment variables file

   ```bash
   $ cp .env.example .env
   ```

8. Add your [API key](https://beta.openai.com/account/api-keys) to the newly created `.env` file

9. Run the app

   ```bash
   $ flask run
   ```

You should now be able to access the app at [http://localhost:5000](http://localhost:5000)! For the full context behind this example app, check out the [tutorial](https://beta.openai.com/docs/quickstart).
