---
title: save method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
บันทึกภาพไปยังไฟล์


```python
def save(self, filename):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| filename | **str** | เส้นทางไปยังไฟล์ที่ภาพจะถูกบันทึกไว้. |


## save(self, filename, format) {#str-imageformat}
บันทึกภาพไปยังไฟล์ในรูปแบบที่ระบุ


```python
def save(self, filename, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| filename | **str** | เส้นทางไปยังไฟล์ที่ภาพจะถูกบันทึกไว้. |
| format | [`ImageFormat`](/slides/python-net/th/aspose.slides/imageformat) | รูปแบบภาพ. |


## save(self, stream, format) {#iorawiobase-imageformat}
บันทึกภาพไปยังสตรีมในรูปแบบที่ระบุ


```python
def save(self, stream, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมที่ภาพจะถูกบันทึกไว้. |
| format | [`ImageFormat`](/slides/python-net/th/aspose.slides/imageformat) | รูปแบบภาพ. |


## save(self, filename, format, quality) {#str-imageformat-int}
บันทึกภาพไปยังไฟล์ในรูปแบบและคุณภาพที่ระบุ


```python
def save(self, filename, format, quality):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| filename | **str** | เส้นทางไปยังไฟล์ที่ภาพจะถูกบันทึกไว้. |
| format | [`ImageFormat`](/slides/python-net/th/aspose.slides/imageformat) | รูปแบบภาพ. |
| quality | **int** | คุณภาพของภาพที่บันทึก (0 ถึง 100).  <br/><br/>            พารามิเตอร์นี้ส่งผลต่อการบันทึกใน [`ImageFormat.JPEG`](/slides/python-net/th/aspose.slides/imageformat/JPEG) เท่านั้น; สำหรับรูปแบบอื่นทั้งหมดจะถูกละเลย. |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
บันทึกภาพไปยังสตรีมในรูปแบบและคุณภาพที่ระบุ


```python
def save(self, stream, format, quality):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมที่ภาพจะถูกบันทึกไว้. |
| format | [`ImageFormat`](/slides/python-net/th/aspose.slides/imageformat) | รูปแบบภาพ. |
| quality | **int** | คุณภาพของภาพที่บันทึก (0 ถึง 100).  <br/><br/>            พารามิเตอร์นี้ส่งผลต่อการบันทึกใน [`ImageFormat.JPEG`](/slides/python-net/th/aspose.slides/imageformat/JPEG) เท่านั้น; สำหรับรูปแบบอื่นทั้งหมดจะถูกละเลย. |



### ดูเพิ่มเติม
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* enumeration [`ImageFormat`](/slides/python-net/th/aspose.slides/imageformat)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)