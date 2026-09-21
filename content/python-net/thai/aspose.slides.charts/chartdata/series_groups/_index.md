---
title: series_groups property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups คุณสมบัติ
รับกลุ่มของชุดข้อมูล.
            อ่านอย่างเดียว [`IChartSeriesGroupCollection`](/slides/python-net/th/aspose.slides.charts/ichartseriesgroupcollection).

### หมายเหตุ

1) แต่ละกลุ่มของชุดข้อมูลประกอบด้วยชุดข้อมูลที่มีประเภทที่สามารถรวมกันได้ กลุ่มของ 
            ประเภทชุดข้อมูลที่สามารถรวมกันได้ถูกกำหนดและอธิบายด้วย CombinableSeriesTypesGroup 
            enum.
            นอกจากนี้แต่ละกลุ่มของชุดข้อมูลยังประกอบด้วยชุดข้อมูลที่ถูกพล็อตบน 
            แกนหลักหรือแกนทุติยภูมิ (ไม่ใช่กรณีทั้งสองในหนึ่งกลุ่ม).
            ดังนั้นหลักการของการจัดกลุ่มชุดข้อมูลคือการจัดกลุ่มตามประเภทที่กล่าวถึง 
            ด้านบนและโดยประเภทการพล็อตหลัก/ทุติยภูมิ.

2) กลุ่มของชุดข้อมูลประกอบด้วยคุณสมบัติบางอย่างของชุดข้อมูลที่เป็นร่วมกันสำหรับ 
            แต่ละชุดข้อมูลในกลุ่ม ("series group properties").
            "Series group properties" ใน คลาส ChartSeriesGroup เป็น อ่าน/เขียน.
            แต่ละ "series group properties" สามารถมีการฉายแบบอ่านอย่างเดียวในคลาส ChartSeries.

### นิยาม:
```python
@property
def series_groups(self):
    ...
```

### ดูเพิ่มเติม
* คลาส [`ChartData`](/slides/python-net/th/aspose.slides.charts/chartdata)
* คลาส [`IChartSeriesGroupCollection`](/slides/python-net/th/aspose.slides.charts/ichartseriesgroupcollection)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)