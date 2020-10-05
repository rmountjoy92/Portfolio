# Portfolio

Ross Mountjoy's personal portfolio website. Want to run it locally? Follow the instructions below.

## Installing

### Using Docker:
```bash
docker build -t Portfolio .
docker run --publish 5000:5000 Portfolio
```

### Development Server:
Clone repository & navigate to it:

```bash
git clone https://github.com/rmountjoy92/Portfolio.git
cd Portfolio
```

Create virtual environment & activate it:

```bash
python3 -m venv venv
source venv/bin/activate
```

Install requirements:

```bash
pip install -r requirements.txt
```

Start the test server:
```bash
python3 run_test_server.py
 ```



Visit the following address in your browser:  
`http://localhost:5000/`

To view/test the rest API go to:  
`http://localhost:5000/api`

### Stack
- (optionally) Docker
- Flask (Python 3.8)
- HTML5/Jinja2
- Bootstrap CSS
- RestX, SwaggerUI