This program navigates to a directory, selects all the image files, and scrolls them in a viewer.

There are buttons to start, stop, speed adjustment of the slideshow.

valid_exts = (".png", ".jpg", ".jpeg", ".gif", ".bmp", ".webp")

#steps to create EXE for one-click use of app place pythonSlideShow.py in a folder (example:C:\Users\Admin\Desktop\work\Python\PythonApps) along with txt_studio.ico. #Goto command prompt

pip install pyinstaller

pyinstaller --noconsole --onefile --icon C:\Users\Admin\Desktop\work\Python\PythonApps\txt_studio.ico C:\Users\Admin\Desktop\work\Python\PythonApps\pythonSlideShow.py

It will create EXE in folder C:\Users\Admin\dist by default. Copy EXE to desired location.
