---
title: pie_split_by property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by คุณสมบัติ
ระบุวิธีการกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สอง 
บนแผนภูมิ pie-of-pie หรือ bar-of-pie
คุณสมบัตินี้ไม่ใช่ของซีรีส์นี้เท่านั้น แต่ของทุกซีรีส์ในกลุ่มซีรีส์พาเรนต์ 
– นี่คือการฉายของคุณสมบัติกลุ่มที่เหมาะสม และคุณสมบัตินี้ 
เป็นแบบอ่าน-อย่างเดียว
ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มซีรีส์พาเรนต์
ใช้คุณสมบัติ ParentSeriesGroup.PieSplitBy แบบอ่าน/เขียนเพื่อเปลี่ยนค่า
อ่าน-อย่างเดียว [`PieSplitType`](/slides/python-net/th/aspose.slides.charts/piesplittype).

### หมายเหตุ

1) นี่คือการฉายของคุณสมบัติ ParentSeriesGroup.PieSplitBy.
2) หากค่าคุณสมบัติเป็น PieSplitType.Custom คุณสามารถกำหนดข้อมูลการแยกแบบกำหนดเอง 
ด้วยคุณสมบัติ ParentSeriesGroup.PieSplitCustomPoints.

### คำนิยาม:
```python
@property
def pie_split_by(self):
    ...
```

### ดูเพิ่มเติม
* คลาส [`IChartSeries`](/slides/python-net/th/aspose.slides.charts/ichartseries)
* enumeration [`PieSplitType`](/slides/python-net/th/aspose.slides.charts/piesplittype)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)