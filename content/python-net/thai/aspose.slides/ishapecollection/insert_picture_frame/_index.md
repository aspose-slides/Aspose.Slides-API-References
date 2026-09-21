---
title: insert_picture_frame method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ishapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
สร้างกรอบรูปภาพใหม่ที่บรรจุภาพที่ระบุและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ

### คืนค่า

ออบเจกต์ที่สร้างใหม่ [`IPictureFrame`](/slides/python-net/th/aspose.slides/ipictureframe).



```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีเริ่มจากศูนย์ที่ใช้เพื่อแทรกกรอบรูปภาพ |
| shape_type | [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype) | ระบุประเภทรูปทรงที่อยู่ใน [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype)<br/><br/>            ยกเว้นรูปแบบของเส้นทั้งหมด:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | พิกัด x ของกรอบรูปภาพ หน่วยเป็นจุด |
| y | **float** | พิกัด y ของกรอบรูปภาพ หน่วยเป็นจุด |
| width | **float** | ความกว้างของกรอบรูปภาพ หน่วยเป็นจุด |
| height | **float** | ความสูงของกรอบรูปภาพ หน่วยเป็นจุด |
| image | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) ที่จะแสดงในกรอบรูปภาพ |



### ดูเพิ่มเติม
* คลาส [`IPictureFrame`](/slides/python-net/th/aspose.slides/ipictureframe)
* คลาส [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/th/aspose.slides/shapetype)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)