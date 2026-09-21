---
title: compress_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
บีบอัดภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่ระบุ โดยอาจลบส่วนที่ถูกครอปออกได้

### ผลลัพธ์

A **bool** indicating whether the image was successfully compressed. Returns **True** if the image was resized or cropped, otherwise **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | ถ้าเป็น true เมธอดจะลบส่วนที่ถูกครอปออกจากภาพ ซึ่งอาจทำให้ขนาดลดลงเพิ่มเติม |
| resolution | [`PicturesCompression`](/slides/python-net/th/aspose.slides.export/picturescompression) | ความละเอียดเป้าหมายสำหรับการบีบอัด ระบุเป็นค่าใน enum [`PicturesCompression`](/slides/python-net/th/aspose.slides.export/picturescompression) |

### หมายเหตุ

เมธอดนี้เปลี่ยนขนาดและความละเอียดของภาพคล้ายกับฟีเจอร์ของ PowerPoint “Picture Format -> Compress Pictures”

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Throw เมื่อความละเอียดไม่เป็นค่าที่ถูกต้อง |

## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
บีบอัดภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่ระบุ โดยอาจลบส่วนที่ถูกครอปออกได้

### ผลลัพธ์

A **bool** indicating whether the image was successfully compressed. Returns **True** if the image was resized or cropped, otherwise **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | ถ้าเป็น true เมธอดจะลบส่วนที่ถูกครอปออกจากภาพ ซึ่งอาจทำให้ขนาดลดลงเพิ่มเติม |
| resolution | **float** | ความละเอียดเป้าหมายใน DPI ค่านี้ต้องเป็นค่าบวกและกำหนดว่าจะปรับขนาดภาพอย่างไร |

### หมายเหตุ

เมธอดนี้เปลี่ยนขนาดและความละเอียดของภาพคล้ายกับฟีเจอร์ของ PowerPoint “Picture Format -> Compress Pictures”

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Throw เมื่อความละเอียดไม่เป็นค่าบวก |

### ดูเพิ่มเติม
* คลาส [`PictureFillFormat`](/slides/python-net/th/aspose.slides/picturefillformat)
* enumeration [`PicturesCompression`](/slides/python-net/th/aspose.slides.export/picturescompression)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)