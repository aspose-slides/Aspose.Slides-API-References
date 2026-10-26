---
title: add_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
เพิ่มสำเนาของรูปภาพจากงานนำเสนออื่น

### Returns

รูปภาพที่เพิ่ม



```python
def add_image(self, image_source):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) | Source image. |


## add_image(self, image) {#iimage}
เพิ่มรูปภาพไปยังงานนำเสนอ

### Returns

รูปภาพที่เพิ่ม



```python
def add_image(self, image):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/th/aspose.slides/iimage) | Image to add. |

### Remarks

วิธีนี้จะแปลงไฟล์ WMF/EMF เป็นภาพ PNG แบบ raster ก่อนใส่ลงในงานนำเสนอ


## add_image(self, stream) {#iorawiobase}
เพิ่มรูปภาพไปยังงานนำเสนอจากสตรีม

### Returns

รูปภาพที่เพิ่ม



```python
def add_image(self, stream):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream to add image from. |

### Remarks

วิธีนี้สามารถเพิ่มไฟล์ WMF/EMF ไปยังงานนำเสนอโดยไม่ต้องแปลงเป็นภาพ PNG แบบ raster


## add_image(self, buffer) {#bytes}
เพิ่มรูปภาพไปยังงานนำเสนอจากบัฟเฟอร์ที่ระบุ

### Returns

รูปภาพที่เพิ่ม



```python
def add_image(self, buffer):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| buffer | **bytes** | Buffer. |


## add_image(self, svg_image) {#isvgimage}
เพิ่มรูปภาพไปยังงานนำเสนอจากออบเจ็กต์ Svg

### Returns

รูปภาพที่เพิ่ม



```python
def add_image(self, svg_image):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/th/aspose.slides/isvgimage) | Svg image object [`ISvgImage`](/slides/python-net/th/aspose.slides/isvgimage) |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | เมื่อพารามิเตอร์ svgImage มีค่าเป็น None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
สร้างและเพิ่มรูปภาพไปยังงานนำเสนอจากสตรีม

### Returns

เพิ่ม [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream to add image file from. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/th/aspose.slides/loadingstreambehavior) | The behavior which will be applied to the stream. |



### See Also
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* คลาส [`ImageCollection`](/slides/python-net/th/aspose.slides/imagecollection)
* คลาส [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage)
* คลาส [`ISvgImage`](/slides/python-net/th/aspose.slides/isvgimage)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/th/aspose.slides/loadingstreambehavior)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)