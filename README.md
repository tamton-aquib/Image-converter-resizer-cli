# Imreco

Image-Resizer-Converter.
A python cli program to perform basic stuff to images using opencv. (WIP)
Planning to include resizer and converter functions.

### Usage:
```python
git clone https://github.com/tamton-aquib/imreco.git
cd imreco
python3 main.py --help

# Syntax:
python3 main.py resize  -i <input_file> -o <output_file> -s 300x400
python3 main.py convert -i <input_file> -o <output_file> 
```

### TODOS:
- [x] Resizer: To change diamension of the provided image, and save it to a new file.
- [x] Converter: To change file formats from png to jpg, etc.
- [x] Config: Add user config options. (maybe argparse or typer)
- [ ] Checks multiple files or a directory.
