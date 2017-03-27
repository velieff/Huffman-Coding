# Huffman Coding (File Archiver)
Data Structures Course<br>
Solution to course project<br>
Faculty of Mathematics and Informatics of Sofia University<br>
Winter semester 2016/2017

##	Valid commands
* pack `<directory>` `<archivename>` - builds an archive with name `<archivename>`, where are packed the files and directories from `<directory>`
* unpack `<archivename>` `<directory>` - unpacks `<archivename>` to the folder `<directory>`
* list `<archivename>` - prints the list of the files and directories, which are packed in `<archivename>`

## Examples
For example, there is a folder in D:\ (*D:\folder*) which contains one file (*D:\folder\file.txt*)<br>
and one folder (*D:\folder\folder1*) which contains one file (*D:\folder\folder1\file1.txt*).
* Packing<br>
Command: `pack D:\folder D:\archive.bin`
```
Packing...
file.txt - the file is successfully packed!
folder1 - the directory is successfully packed!
folder1\file1.txt - the file is successfully packed!
Packing successfully finished!
```
* Unpacking<br>
Command: `unpack D:\archive.bin D:\unpacked`
```
Unpacking...
D:\unpacked - the directory is successfully created!
file.txt - the file is successfully unpacked!
folder1 - the directory is successfully unpacked!
folder1\file1.txt - the file is successfully unpacked!
Unpacking successfully finished!
```
* List<br>
Command: `list D:\archive.bin`
```
List:
1: file.txt - file
2: folder1 - directory
3: folder1\file1.txt - file
```
