# TEDS22_2024
This is the repository for the Embedded and Distributed AI (Autumn 2024) course at Jönköping University.

## Environment Setup

First, make sure you have installed Python, Node.js, Git, Mosquitto MQTT Server, Visual Studio Code, and Android Studio on your computer.

### Python (install version 3.9.13)
- Windows: [instructions](https://docs.python.org/3/using/windows.html) and [download](https://www.python.org/downloads/windows).
- Ubuntu: [instructions](https://docs.python.org/3/using/unix.html) and [download](https://www.python.org/downloads/source).
- MacOS: [instructions](https://docs.python.org/3/using/mac.html) and [download](https://www.python.org/downloads/mac-osx).
### Node.js (latest version)
- Windows/Ubuntu/MacOS [download](https://nodejs.org/en/download).
- Run the following command in your terminal:  
`npm install ijavascript -g`
### Git (install latest version)
- Windows/Ubuntu/MacOS: [instructions](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [downloads](https://git-scm.com/downloads).
### Mosquitto MQTT Server (latest version)
- Windows/Ubuntu/MacOS [download](https://mosquitto.org/download).
### Visual Studio Code (install latest version)
- Windows: [instructions](https://code.visualstudio.com/docs/setup/windows) and [download](https://code.visualstudio.com/download).
- Ubuntu: [instructions](https://code.visualstudio.com/docs/setup/linux) and [download](https://code.visualstudio.com/download).
- MacOS: [instructions](https://code.visualstudio.com/docs/setup/mac) and [download](https://code.visualstudio.com/download).
### Android Studio (latest version)
- Windows/Ubuntu/MacOS [download](https://developer.android.com/studio).

Then follow the steps below to download the Github repository and start working with the workshop notebooks.

1. Open a terminal window:
   - Windows: \<Windows\> + \<X\> followed by \<A\> (click "Yes").
   - Ubuntu: \<Ctrl\> + \<Alt\> + \<T\>
   - MacOS: \<Cmd\> + \<Space\>, type "*Terminal*" + \<Return\>.
2. Choose a folder where you want to install the Github repository for this course, e.g. your home folder
   - Windows: `cd %USERPROFILE%`
   - Ubuntu/MacOS: `cd ~`
3. Download the Github repository to the folder "teds20" with the command `git clone https://github.com/paga-ju/teds22_2024.git teds22`
4. Change to the *teds22* folder by executing the command `cd teds22`
5. Create a Python virtual environment with the command `python -m venv .venv`
6. Activate the virtual environment (you should see "*(.venv)*" as part of your command prompt when done)
   - Windows: `.venv\Scripts\activate`
   - Ubuntu/MacOS: `source .venv\bin\activate`
7. Install the necessary python packages in the virtual environment with the command `pip install -r requirements.txt`
8. Launch Visual Studio Code with the command `code .`
9. Wait for Visual Studio Code to start.
10. In Visual Studio Code, open the *Command Palette*
    - Windows/Ubuntu: \<Ctrl\> + \<Shift\> + \<P\>
    - MacOS: \<Cmd\> + \<Shift\> + \<P\>
11. Type in "*Python: Select Interpreter*"
12. Choose *Enter Interpreter Path...*
13. Choose *Find...*
14. Browse to and select the Python Interpreter in your virtual environment
    - Windows: `.venv\Scripts\python.exe`
    - Ubuntu/MacOS: `.venv/bin/python`
15. Open up a notebook in one of the Workshop1 folders, e.g. *Workshop1/1_read_display_write_images.ipynb*
16. In the upper-right of the IDE, you will see the text "*Trusted | Jupyter Server: local | Python 3.9.13 64-bit ('.venv: venv): idle*" (or something similar). Click on the last part of that text, i.e. with the text "*Python 3.9.13 64-bit ('.venv: venv): idle*" (or similar).
17. Select the Python Interpreter again that your chose in step 5 above (you should see the complete path to the interpreter as one of the choices).

Now Visual Studio Code is configured to run Python code, and Jupyter Notebooks, from your virtual environment, i.e. now you can open any notebook and execute the notebook cells.
