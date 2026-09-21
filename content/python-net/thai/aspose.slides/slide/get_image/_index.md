---
title: get_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
ส่งคืนอ็อบเจ็กต์ Thumbnail Image (ขนาดจริง 20%)。


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposepydrawingsize}
ส่งคืนอ็อบเจ็กต์ Thumbnail Image ที่มีขนาดที่ระบุ

### ส่งคืน

Image object.



```python
def get_image(self, image_size):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | ขนาดของภาพที่ต้องการสร้าง. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
ส่งคืนอ็อบเจ็กต์ Thumbnail tiff image ที่มีพารามิเตอร์ที่ระบุ

### ส่งคืน

Image object.



```python
def get_image(self, options):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/th/aspose.slides.export/itiffoptions) | ตัวเลือก Tiff. |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | เกิดขึ้นเมื่อ options.SlideLayoutOption เป็น NotesCommentsLayoutingOptions และ property NotesPosition มีค่าเป็น NotesPositions.BottomFull. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
ส่งคืนอ็อบเจ็กต์ Thumbnail Image

### ส่งคืน

Image object.



```python
def get_image(self, options):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions) | ตัวเลือกการเรนเดอร์. |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | เกิดขึ้นเมื่อ notesCommentsLayouting.NotesPosition มีค่าเป็น NotesPositions.BottomFull |
 


## get_image(self, scale_x, scale_y) {#float-float}
ส่งคืนอ็อบเจ็กต์ Thumbnail Image ด้วยการปรับสเกลแบบกำหนดเอง

### ส่งคืน

IImage object.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| scale_x | **float** | ค่าที่ใช้ปรับสเกล Thumbnail นี้ในแนวแกน x. |
| scale_y | **float** | ค่าที่ใช้ปรับสเกล Thumbnail นี้ในแนวแกน y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
ส่งคืนอ็อบเจ็กต์ Thumbnail Image ที่มีขนาดที่ระบุ

### ส่งคืน

Image object.



```python
def get_image(self, options, image_size):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions) | ตัวเลือกการเรนเดอร์. |
| image_size | **aspose.slides.Size** | ขนาดของภาพที่ต้องการสร้าง. |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | เกิดขึ้นเมื่อ options.SlideLayoutOption เป็น NotesCommentsLayoutingOptions และ property NotesPosition มีค่าเป็น NotesPositions.BottomFull. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
ส่งคืนอ็อบเจ็กต์ Thumbnail Image ด้วยการปรับสเกลแบบกำหนดเอง

### ส่งคืน

Bitmap objects.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions) | ตัวเลือกการเรนเดอร์. |
| scale_x | **float** | ค่าที่ใช้ปรับสเกล Thumbnail นี้ในแนวแกน x. |
| scale_y | **float** | ค่าที่ใช้ปรับสเกล Thumbnail นี้ในแนวแกน y. |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | เกิดขึ้นเมื่อ notesCommentsLayouting.NotesPosition มีค่าเป็น NotesPositions.BottomFull |
 


### ดูเพิ่มเติม
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* คลาส [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions)
* คลาส [`ITiffOptions`](/slides/python-net/th/aspose.slides.export/itiffoptions)
* คลาส [`Slide`](/slides/python-net/th/aspose.slides/slide)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)