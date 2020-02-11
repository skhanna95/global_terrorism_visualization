# Global terrorism
# visualization project


## For mac/ubuntu users:

1. open 3 terminals.
2. In each terminal cd to the directory. Example: cd users/Downloads/final_project
3. In the first terminal type the following command:
	- ```pip install -r requirements.txt```
	- ```cd static_display```
	- ```python callback.py```
4. In the second terminal type:
	- ```cd story_mode``` 
	
	- ```python final.py```

5. In the third terminal type:
	- ```cd forced_layout```
	- ```python -m http.server 10000```

6. Copy and paste the link in your browser: ```http://0.0.0.0:10000```



## For windows users:

1. Download anaconda
2. Open anaconda command prompt
3. cd to the folder directory example: cd users/Downloads/final_project
4. Type: ```pip install -r requirements.txt```
5. Type: 
	- ```cd story_mode```
	- ```python final.py```

6. Open another anaconda command prompt
7. cd to the project folder
8. Type:
	- ```cd static_display```
	- ```cd Callback.py```

9. open a new command prompt.
10. cd to the project folder
11. Type:
	- ```cd forced_layout```
	- ```python -m http.server 10000```
12. Copy and paste the following link in your browser to see the demo: ```http://127.0.0.1:10000```



Note if the story_mode or static_display prompts returns an error stating that port in use then:
1. Open the python file
2. Go to the last line of the file starting with ```app.run_server(debug=True)``` and change it to: ```app.run_server(debug=True,port=9999)```
