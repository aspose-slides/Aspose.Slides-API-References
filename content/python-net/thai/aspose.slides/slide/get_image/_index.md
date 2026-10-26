---
title: get_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
คืนค่า Thumbnail Image วัตถุ (20% ของขนาดจริง).


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
คืนค่า Thumbnail Image วัตถุ พร้อมขนาดที่ระบุ.

### คืนค่า

Image วัตถุ.



```python
def get_image(self, image_size):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/th/aspose.slides/size) | ขนาดของภาพที่สร้าง |


## get_image(self, options) {#asposeslidesexportitiffoptions}
คืนค่า Thumbnail tiff image วัตถุ พร้อมพารามิเตอร์ที่ระบุ.

### คืนค่า

Image วัตถุ.



```python
def get_image(self, options):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/th/aspose.slides.export/itiffoptions) | ตัวเลือก Tiff |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | เกิดเมื่อ options.SlideLayoutOption เป็น NotesCommentsLayoutingOptions และ property NotesPosition มีค่า NotesPositions.BottomFull. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
คืนค่า Thumbnail Image วัตถุ.

### คืนค่า

Image วัตถุ.



```python
def get_image(self, options):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions) | ตัวเลือกการเรนเดอร์ |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | เกิดเมื่อ notesCommentsLayouting.NotesPosition มีค่า NotesPositions.BottomFull |


## get_image(self, scale_x, scale_y) {#float-float}
คืนค่า Thumbnail Image วัตถุ พร้อมการสเกลที่กำหนดเอง.

### คืนค่า

IImage วัตถุ.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| scale_x | **float** | ค่าที่ใช้สเกล Thumbnail ในทิศทางแกน x. |
| scale_y | **float** | ค่าที่ใช้สเกล Thumbnail ในทิศทางแกน y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
คืนค่า Thumbnail Image วัตถุ พร้อมขนาดที่ระบุ.

### คืนค่า

Image วัตถุ.



```python
def get_image(self, options, image_size):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions) | ตัวเลือกการเรนเดอร์ |
| image_size | [`Size`](/slides/python-net/th/aspose.slides/size) | ขนาดของภาพที่สร้าง |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | เกิดเมื่อ options.SlideLayoutOption เป็น NotesCommentsLayoutingOptions และ property NotesPosition มีค่า NotesPositions.BottomFull. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
คืนค่า Thumbnail Image วัตถุ พร้อมการสเกลที่กำหนดเอง.

### คืนค่า

Bitmap วัตถุ.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions) | ตัวเลือกการเรนเดอร์ |
| scale_x | **float** | ค่าที่ใช้สเกล Thumbnail ในทิศทางแกน x. |
| scale_y | **float** | ค่าที่ใช้สเกล Thumbnail ในทิศทางแกน y. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | เกิดเมื่อ notesCommentsLayouting.NotesPosition มีค่า NotesPositions.BottomFull |



### ดูเพิ่มเติม
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* คลาส [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions)
* คลาส [`ITiffOptions`](/slides/python-net/th/aspose.slides.export/itiffoptions)
* คลาส [`Slide`](/slides/python-net/th/aspose.slides/slide)
* คลาส [`Size`](/slides/python-net/th/aspose.slides/size)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)