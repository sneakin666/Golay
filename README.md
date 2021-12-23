# Encode and decode images with binary Golay code
<div align="center">
  
<img alt="GitHub (Pre-)Release Date" src="https://img.shields.io/github/release-date-pre/sneakin666/Golay">
<img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/sneakin666/Golay">
  
[Encoding image](#encoding-image) •  
[Decoding image](#decoding-image) • 
  
  </div>
  
  #
  
For this software implementation to work, 2 libraries are needed: *docopt*, *matplotlib*, *numpy*, *opencv* and *pickle*.


*docopt*, *matplotlib*, *numpy*, *opencv* and *pickle* must be installed with the following console command:

```sh
pip3 install docopt
```
```sh
pip3 install matplotlib
```
```sh
pip3 install numpy
```
```sh
pip3 install opencv-python
```
```sh
pip3 install pickle
```

To display a small instruction about the program, type *-h* or *-help*.

```sh
python Golay.py --help
```

![](pic/1.jpg)

# Encoding image


To do this, simply enter the command:

```sh
python Golay.py --encoding <path> <path2>
```
For example:

![](pic/2.jpg)

After using this command in suck path, which was typed in <path2> will be created .pckl file

# Decoding image
  
To do this, simply enter the command:

```sh
python Golay.py --decoding <path> <path2>
```
For example:

![](pic/3.jpg)
  
In <path> should be typed path to .plck file
The result of this command will be image file
  
#

## Authors

* **Ivan Kurilchik** - [GitHub](https://github.com/sneakin666)

## License

This project is licensed under the GNU ver.3 License.
