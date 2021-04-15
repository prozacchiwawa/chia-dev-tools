Chialisp Dev Utility
=======

Install
-------

```
git clone https://github.com/Quexington/chialisp_dev_utility.git
cd chialisp_dev_utility
python3 -m venv venv #py on Windows
#Optionally add this to PATH, you will need it every time you are using the utility
. .\venv\bin\activate #.\venv\Scripts\activate on windows
pip install -e .
```

Initialize a hello world project
-------
```
mkdir My-Chia-Project
cd My-Chia-Project
chialisp init
```

Run the hello world project
-------
```
chialisp build
py helloworld.py
```

All current commands
-------
```
chialisp init #creates a 'Hello World' script in the current directory
chialisp build <optional clvm filename> #build all .clvm files into .hex files or just the specified one
```
