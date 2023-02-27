### How to run the project:

Clone the repository and open it in the command-line interface:

```
git clone https://github.com/practicum-com/kittygram-en.git
```

```
cd kittygram-en
```

Create and activate a virtual environment:

```
python3 -m venv env
```

* In Linux/MacOS

    ```
    source env/bin/activate
    ```

* In Windows

    ```
    source env/scripts/activate
    ```

Install the dependencies from the requirements.txt file:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Run migrations:

```
python3 manage.py migrate
```

Run the project:

```
python3 manage.py runserver
```
