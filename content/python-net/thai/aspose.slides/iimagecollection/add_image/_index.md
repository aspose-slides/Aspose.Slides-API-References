---
title: add_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
เพิ่มรูปภาพไปยังการนำเสนอ

### ผลลัพธ์

เพิ่มรูปภาพแล้ว



```python
def add_image(self, image):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/th/aspose.slides/iimage) | รูปภาพที่จะเพิ่ม |

### หมายเหตุ

เมธอดนี้แปลงไฟล์เมตาฟไฟล์ WMF/EMF ให้เป็นภาพ PNG แบบราสเตอร์ก่อนใส่ลงในการนำเสนอ


## add_image(self, stream) {#iorawiobase}
เพิ่มรูปภาพไปยังการนำเสนอจากสตรีม

### ผลลัพธ์

เพิ่มรูปภาพแล้ว



```python
def add_image(self, stream):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมที่ใช้เพิ่มรูปภาพจาก |

### หมายเหตุ

เมธอดนี้สามารถเพิ่มไฟล์เมตาฟไฟล์ WMF/EMF ไปยังการนำเสนอโดยไม่ต้องแปลงเป็นภาพ PNG แบบราสเตอร์


## add_image(self, buffer) {#bytes}
เพิ่มรูปภาพไปยังการนำเสนอจากบัฟเฟอร์ที่ระบุ

### ผลลัพธ์

เพิ่มรูปภาพแล้ว



```python
def add_image(self, buffer):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| buffer | **bytes** | บัฟเฟอร์ |


## add_image(self, image_source) {#ippimage}
เพิ่มสำเนาของรูปภาพจากการนำเสนออื่น

### ผลลัพธ์

เพิ่มรูปภาพแล้ว



```python
def add_image(self, image_source):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) | รูปภาพต้นทาง |


## add_image(self, svg_image) {#isvgimage}
เพิ่มรูปภาพไปยังการนำเสนอจากอ็อบเจ็กต์ SVG

### ผลลัพธ์

เพิ่มรูปภาพแล้ว



```python
def add_image(self, svg_image):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/th/aspose.slides/isvgimage) | อ็อบเจ็กต์ภาพ SVG [`ISvgImage`](/slides/python-net/th/aspose.slides/isvgimage) |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | จะถูกโยนเมื่อพารามิเตอร์ svgImage มีค่า None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
สร้างและเพิ่มรูปภาพไปยังการนำเสนอจากสตรีม

### ผลลัพธ์

เพิ่ม [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | สตรีมที่ใช้เพิ่มไฟล์รูปภาพจาก |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/th/aspose.slides/loadingstreambehavior) | พฤติกรรมที่จะถูกใช้กับสตรีม |



### ดูเพิ่มเติม
* class [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* class [`IImageCollection`](/slides/python-net/th/aspose.slides/iimagecollection)
* class [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage)
* class [`ISvgImage`](/slides/python-net/th/aspose.slides/isvgimage)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/th/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)