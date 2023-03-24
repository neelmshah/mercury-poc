# Mercury-PoC
Convert Jupyter notebook into interactive web apps &amp; more.

Let's refer to [Mercury](https://runmercury.com/) official site


## Installation

Create Python Virtual Environment

```
python3 -m venv env
```


Activate virtual environment

```
source venv/bin/activate
```


Install packages

```
pip install -r requirements.txt 
```


Add notebook

```
add sample_report.ipynb 
```

Run mercury service

```
mercury run
```

### Notebook embedding

You can easily embed notebooks served with Mercury.

1. Open browser http://localhost:8000/
2. Click on sample report card
3. Copy page URL (i.e. http://127.0.0.1:8000/app/sample_report) 
4. Add /embed at the end of the URL address.
5. Insert iframe in the website where you would like to embed a notebook.

```
<iframe src="http://127.0.0.1:8000/app/sample_report/embed" height="700px" width="1200px"></iframe>
```




