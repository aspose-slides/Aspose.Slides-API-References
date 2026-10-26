---
title: add_picture_frame method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
สร้างกรอบรูปภาพใหม่ที่ประกอบด้วยภาพที่ระบุและเพิ่มเข้าที่ส่วนท้ายของ
            คอลเลกชันรูปร่าง.

### คืนค่า

ออบเจ็กต์ที่สร้างใหม่ [`IPictureFrame`](/slides/python-net/th/aspose.slides/ipictureframe).



```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | ระบุประเภทของรูปทรงที่อยู่ใน [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype),<br/><br/>            ยกเว้นประเภทเส้นทั้งหมด:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | พิกัด x ของกรอบรูปภาพ, มีหน่วยเป็น points. |
| y | **float** | พิกัด y ของกรอบรูปภาพ, มีหน่วยเป็น points. |
| width | **float** | ความกว้างของกรอบรูปภาพ, มีหน่วยเป็น points. |
| height | **float** | ความสูงของกรอบรูปภาพ, มีหน่วยเป็น points. |
| image | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) ที่จะแสดงในกรอบรูปภาพ. |



### ดูเพิ่มเติม
* คลาส [`IPictureFrame`](/slides/python-net/th/aspose.slides/ipictureframe)
* คลาส [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage)
* คลาส [`ShapeCollection`](/slides/python-net/th/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)