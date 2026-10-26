---
title: add_picture_frame method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/ishapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
สร้างเฟรมรูปภาพใหม่ที่มีภาพที่ระบุและเพิ่มเข้าไปที่ส่วนท้ายของ
            คอลเลกชันรูปร่าง.

### ส่งคืน

อ็อบเจกต์ที่สร้างขึ้นใหม่ [`IPictureFrame`](/slides/python-net/th/aspose.slides/ipictureframe).



```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | ระบุประเภทรูปทรงที่อยู่ใน [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype),<br/><br/>            ยกเว้นสำหรับเส้นทุกประเภท:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | พิกัด x ของเฟรมรูปภาพ, หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของเฟรมรูปภาพ, หน่วยเป็นจุด. |
| width | **float** | ความกว้างของเฟรมรูปภาพ, หน่วยเป็นจุด. |
| height | **float** | ความสูงของเฟรมรูปภาพ, หน่วยเป็นจุด. |
| image | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) เพื่อแสดงในเฟรมรูปภาพ. |



### ดูเพิ่มเติม
* คลาส [`IPictureFrame`](/slides/python-net/th/aspose.slides/ipictureframe)
* คลาส [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)