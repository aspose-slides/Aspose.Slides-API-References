---
title: series_groups property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups คุณสมบัติ
Gets the groups of series.
อ่านอย่างเดียว [`IChartSeriesGroupCollection`](/slides/python-net/th/aspose.slides.charts/ichartseriesgroupcollection).

### คำอธิบาย

1) แต่ละกลุ่มของ series มี series ที่มีประเภทที่สามารถรวมกันได้. กลุ่มของ 
            ประเภท series ที่สามารถรวมกันได้ที่กำหนดและอธิบายด้วย CombinableSeriesTypesGroup 
            enum.
            นอกจากนี้แต่ละกลุ่มของ series มี series ที่ถูกวาดบน 
            แกนหลักหรือแกนรอง (ไม่ใช่ทั้งสองกรณีในกลุ่มเดียว).
            ดังนั้นหลักการของการจัดกลุ่ม series คือการจัดกลุ่มตามประเภทที่กล่าวถึง 
            ข้างต้นและตามประเภทการวาดบนแกนหลัก/แกนรอง.

            2) กลุ่มของ series มีบางคุณสมบัติของ series ที่เป็นทั่วไปสำหรับ 
            แต่ละ series ในกลุ่ม ("คุณสมบัติของกลุ่ม series").
            "คุณสมบัติของกลุ่ม series" ในคลาส ChartSeriesGroup เป็น อ่าน/เขียน.
            แต่ละ "คุณสมบัติของกลุ่ม series" สามารถมีการฉายแบบอ่านอย่างเดียวในคลาส ChartSeries.

### คำนิยาม:
```python
@property
def series_groups(self):
    ...
```

### ดูเพิ่มเติม
* คลาส [`IChartData`](/slides/python-net/th/aspose.slides.charts/ichartdata)
* คลาส [`IChartSeriesGroupCollection`](/slides/python-net/th/aspose.slides.charts/ichartseriesgroupcollection)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)