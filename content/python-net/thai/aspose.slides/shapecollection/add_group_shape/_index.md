---
title: add_group_shape method
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/shapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
สร้างรูปกลุ่มเปล่าขึ้นใหม่และเพิ่มเข้าไปยังตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง
            กรอบของกลุ่มจะปรับขนาดโดยอัตโนมัติเพื่อให้พอกับรูปร่างใด ๆ ที่เพิ่มเข้าไป

### คืนค่า

[`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape) ที่สร้างขึ้นใหม่.



```python
def add_group_shape(self):
    ...
```



## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
สร้างรูปกลุ่มใหม่, แปลงภาพ SVG ที่ระบุเป็นรูปแบบแยกเดี่ยว,
            และเพิ่มกลุ่มที่ได้ลงในตำแหน่งสุดท้ายของคอลเลกชันรูปร่าง

### คืนค่า

[`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape) ที่สร้างขึ้นใหม่.



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/th/aspose.slides/isvgimage) | [`ISvgImage`](/slides/python-net/th/aspose.slides/isvgimage) ที่มีเนื้อหาเวกเตอร์เพื่อแปลงเป็นรูปร่าง |
| x | **float** | พิกัด x ของกรอบของกลุ่ม, หน่วยเป็นพอยต์ |
| y | **float** | พิกัด y ของกรอบของกลุ่ม, หน่วยเป็นพอยต์ |
| width | **float** | ความกว้างของกรอบของกลุ่ม, หน่วยเป็นพอยต์ |
| height | **float** | ความสูงของกรอบของกลุ่ม, หน่วยเป็นพอยต์ |



### ดูเพิ่มเติม
* คลาส [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape)
* คลาส [`ISvgImage`](/slides/python-net/th/aspose.slides/isvgimage)
* คลาส [`ShapeCollection`](/slides/python-net/th/aspose.slides/shapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)