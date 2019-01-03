from flask import flask 

app=Flask(__name__)

@app.route("<script.name>")
 def index():
  return "Hello {name}
 
