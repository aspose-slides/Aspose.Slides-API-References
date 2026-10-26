---
title: formula property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.animation/point/formula/
weight: 20
---
## คุณสมบัติ formula
สูตรภายในค่า, แอตทริบิวต์จาก, ถึง, ทีละ สามารถประกอบด้วย:
            ตัวดำเนินการคณิตศาสตร์มาตรฐาน: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            ค่าคงที่: ‘pi’ ‘e’
            ตัวดำเนินการเงื่อนไข: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            ตัวดำเนินการเปรียบเทียบ: '==', '>=', '', '!=', '!'
            ตัวดำเนินการตรีโกณมิติ: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            ลอการิทึมธรรมชาติ ‘ln()’
            การอ้างอิงคุณสมบัติ (host supported properties)
            
            for example: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            อ่าน/เขียน **str**.

### คำนิยาม:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```

### ดูเพิ่มเติม
* คลาส [`Point`](/slides/python-net/th/aspose.slides.animation/point)
* โมดูล [`aspose.slides.animation`](/slides/python-net/th/aspose.slides.animation)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)