---
title: is_visible property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/idatalabelcollection/is_visible/
weight: 120
---
## is_visible คุณสมบัติ
False หมายความว่า data label ไม่แสดงผลโดยค่าเริ่มต้น (และดังนั้น Show*-flags (ShowValue, ...) ของ DefaultDataLabelFormat property จะเป็น false).
            อ่านอย่างเดียว **bool**.

### หมายเหตุ

หาก data label แสดงผลโดยค่าเริ่มต้น คุณสามารถทำให้มันซ่อนโดยค่าเริ่มต้นด้วยเมธอด Hide().
            แต่หาก data label ไม่แสดงผลโดยค่าเริ่มต้น (IsVisible is false) คุณสามารถทำให้ data label "visible 
            by default" โดยตั้งค่า Show*-flags (ShowValue, ...) ของ DefaultDataLabelFormat property
            ให้เป็นสถานะ true.

### นิยาม:
```python
@property
def is_visible(self):
    ...
```

### ดูเพิ่มเติม
* คลาส [`IDataLabelCollection`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)