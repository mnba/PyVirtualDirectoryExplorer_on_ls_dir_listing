## Virtual Directory Explorer GUI (Python) on `ls` or `dir` directory recursive listing
This is **Virtual Directory Explorer** Desktop GUI utility app, written with *Python2* + *wxWidgets*.
 
It is a **File(*) Explorer / browser / navigator for directory listing text files.**

**Allows you to save directory structure once, and browse it later in any other time or any other machine.**

* Takes for input recursive directory listing from either:
  * Linux/Macos/Unix '**ls -laR**' command output or 
  * Windows '**dir /s**' command output and 
* Provides GUI browser for it, the graphical interface to browse/explore the given virtual directory.

It can be considered as **_Directory structure snapshot browser or viewer_**.

Even entire disk filesystem structure can be examined.

### Supported Operating systems: Windows, Macos, Linux

This utility supports all major desktop Operating Systems: Windows, Macos, Linux. Only required support is for Python 2.7 and wxWidgets 2.9+.

### Designed-in Limitations

Since input does not contain other info besides directory/filesystem structure and metainformation generated by dir /s of ls -laR command, it doesn't contain other information such as content of the files, so the browser can't show or provide them.

This is in the first head *directory **structure** snapshot browser*. 

## Screenshots
Screenshot of browser for **_tests/zCTdisk_laR.txt_** file, which was generated by the next command 
```shell
cd /mount/CTDisk/
ls -laR > ../CTdisk_laR.txt
```
  
![Screenshot of v1.0 (Linux)](/screenshots/screenshot-linux1.0s1.png?raw=true "Screenshot of v1.0 (Linux)")

## How to Run it
From command line simply run: `./App.py`

Another option is to run at once with listing-file as argument:
```shell
./App.py  your-dir-s-or-ls-laLR-listing.txt
```
<!---
## Please, report problems in the issues
Thanks!
MA: This comments trick taken from: Comments in Markdown (syntax) - Stack Overflow
https://stackoverflow.com/questions/4823468/comments-in-markdown
add screenshot to READMEs in github repository, How to? (markdown) - Stack Overflow
https://stackoverflow.com/questions/10189356/how-to-add-screenshot-to-readmes-in-github-repository
Markdown Cheatsheet · adam-p/markdown Wiki
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
-->
[//]: # (Another comment, most invisible and most platform independent, ditto)
