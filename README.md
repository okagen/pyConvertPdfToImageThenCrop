# pyConvertPdfToImageThenCrop
Convert a large number of PDF files to image files, then crop them. <br>
大量のPDFファイルを画像ファイルに変換し、その中から画像を切り出す。

## 1 : There are a large number of PDF files stored in pdf directory as below
~~~
Data
├──pdf 
│  ├─Sample-01.pdf
│  ├─Sample-02.pdf
│  ├─Sample-03.pdf
│  ├─ ...
~~~
Image of Sample-01.pdf<br>
<img src="https://github.com/okagen/pyConvertPdfToImageThenCrop/blob/master/Data/img/Sample-01-1.png?raw=true" width="200">

## 2 : Convert PDF files to image files(*.png) then save them into the img directory.
More than 1 files are created if a PDF file has some pages.
~~~
Data
├─img
│  ├─Sample-01-1.png
│  ├─Sample-02-1.png
│  ├─Sample-02-2.png
│  ├─Sample-03-1.png
│  ├─Sample-03-2.png
│  ├─Sample-03-3.png
│  ├─ ...
~~~

## 3 : Crop image files then save them into the img_crop directory.
Create directory with image file name and save the croped image file in it.  
In the case of cropping 4 times, the file structure appears like below.
~~~
Data
├─img_crop
│  ├─Sample-01-1
│  │  ├─Sample-01-1-01.png
│  │  ├─Sample-01-1-02.png
│  │  ├─Sample-01-1-03.png
│  │  ├─Sample-01-1-04.png
│  ├─Sample-02-1
│  │  ├─Sample-02-1-01.png
│  │  ├─Sample-02-1-02.png
│  │  ├─Sample-02-1-03.png
│  │  ├─Sample-02-1-04.png
│  ├─Sample-02-2
│  │  ├─Sample-02-2-01.png
│  │  ├─Sample-02-2-02.png
│  │  ├─Sample-02-2-03.png
│  │  ├─Sample-02-2-04.png
│  ├─Sample-03-1
│  │  ├─Sample-03-1-01.png
│  │  ├─Sample-03-1-02.png
│  │  ├─Sample-03-1-03.png
│  │  ├─Sample-03-1-04.png
│  ├─Sample-03-2
│  │  ├─Sample-03-2-01.png
│  │  ├─Sample-03-2-02.png
│  │  ├─Sample-03-2-03.png
│  │  ├─Sample-03-2-04.png
│  ├─Sample-03-3
│  │  ├─Sample-03-3-01.png
│  │  ├─Sample-03-3-02.png
│  │  ├─Sample-03-3-03.png
│  │  ├─Sample-03-3-04.png
~~~

Image of 4 cropped image files.<br>

|Crop-1|Crop-2|Crop-3|Crop-4|
| :---: | :---: | :---: | :---: |
|<img src="https://github.com/okagen/pyConvertPdfToImageThenCrop/blob/master/Data/img_crop/Sample-01-1/Sample-01-1-01.png?raw=true" alt="Image of Sample-01-1-01.pdf" width="100">|<img src="https://github.com/okagen/pyConvertPdfToImageThenCrop/blob/master/Data/img_crop/Sample-01-1/Sample-01-1-02.png?raw=true" alt="Image of Sample-01-1-02.pdf" width="100">|<img src="https://github.com/okagen/pyConvertPdfToImageThenCrop/blob/master/Data/img_crop/Sample-01-1/Sample-01-1-03.png?raw=true" alt="Image of Sample-01-1-03.pdf" width="100">|<img src="https://github.com/okagen/pyConvertPdfToImageThenCrop/blob/master/Data/img_crop/Sample-01-1/Sample-01-1-04.png?raw=true" alt="Image of Sample-01-1-04.pdf" width="100">|
