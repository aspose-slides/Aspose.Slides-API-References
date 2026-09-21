---
title: compress_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
บีบอัดรูปภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่ระบุ หากต้องการก็สามารถลบส่วนที่ถูกตัดออกได้ด้วย

### คืนค่า

ค่า **bool** ที่บ่งชี้ว่ารูปภาพถูกบีบอัดสำเร็จหรือไม่ คืนค่า **True** หากรูปภาพถูกปรับขนาดหรือถูกตัดออก มิฉะนั้นคืนค่า **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | หากเป็น true เมธอดจะลบส่วนที่ถูกตัดของรูปภาพ ซึ่งอาจทำให้ขนาดลดลงเพิ่มอีก |
| resolution | [`PicturesCompression`](/slides/python-net/th/aspose.slides.export/picturescompression) | ความละเอียดเป้าหมายสำหรับการบีบอัด ระบุเป็นค่าของ enum [`PicturesCompression`](/slides/python-net/th/aspose.slides.export/picturescompression) |

### หมายเหตุ

เมธอดนี้เปลี่ยนขนาดและความละเอียดของรูปภาพเช่นเดียวกับฟีเจอร์ "Picture Format -> Compress Pictures" ของ PowerPoint

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดขึ้นเมื่อความละเอียดไม่มีค่าเป็นที่ถูกต้อง |

## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
บีบอัดรูปภาพโดยลดขนาดตามขนาดของรูปร่างและความละเอียดที่ระบุ หากต้องการก็สามารถลบส่วนที่ถูกตัดออกได้ด้วย

### คืนค่า

ค่า **bool** ที่บ่งชี้ว่ารูปภาพถูกบีบอัดสำเร็จหรือไม่ คืนค่า **True** หากรูปภาพถูกปรับขนาดหรือถูกตัดออก มิฉะนั้นคืนค่า **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | หากเป็น true เมธอดจะลบส่วนที่ถูกตัดของรูปภาพ ซึ่งอาจทำให้ขนาดลดลงเพิ่มอีก |
| resolution | **float** | ความละเอียดเป้าหมายใน DPI ค่าเหล่านี้ต้องเป็นค่าบวกและกำหนดวิธีการปรับขนาดรูปภาพ |

### หมายเหตุ

เมธอดนี้เปลี่ยนขนาดและความละเอียดของรูปภาพเช่นเดียวกับฟีเจอร์ "Picture Format -> Compress Pictures" ของ PowerPoint

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดขึ้นเมื่อความละเอียดไม่เป็นค่าบวก |

### ดูเพิ่มเติม
* คลาส [`IPictureFillFormat`](/slides/python-net/th/aspose.slides/ipicturefillformat)
* enumeration [`PicturesCompression`](/slides/python-net/th/aspose.slides.export/picturescompression)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)