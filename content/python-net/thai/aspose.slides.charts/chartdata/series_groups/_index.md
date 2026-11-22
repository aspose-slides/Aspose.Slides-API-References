---
title: series_groups property
second_title: Aspose.Slides for Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups คุณสมบัติ
รับกลุ่มของซีรีส์.
            อ่านอย่างเดียว [`IChartSeriesGroupCollection`](/slides/python-net/th/aspose.slides.charts/ichartseriesgroupcollection).

### หมายเหตุ

1) แต่ละกลุ่มของซีรีส์ประกอบด้วยซีรีส์ที่มีประเภทที่สามารถรวมกันได้. กลุ่มของประเภทซีรีส์ที่สามารถรวมกันได้ถูกกำหนดและอธิบายด้วย enum CombinableSeriesTypesGroup. นอกจากนี้แต่ละกลุ่มของซีรีส์ยังประกอบด้วยซีรีส์ที่ถูกพล็อตบนแกนหลักหรือบนแกนรอง (ไม่ใช่ทั้งสองกรณีในกลุ่มเดียว). ดังนั้น หลักการของการจัดกลุ่มซีรีส์คือการจัดกลุ่มตามประเภทที่กล่าวถึงข้างต้นและตามประเภทการพล็อตหลัก/รอง.

2) กลุ่มของซีรีส์ประกอบด้วยคุณสมบัติบางอย่างของซีรีส์ที่เป็นทั่วไปสำหรับแต่ละซีรีส์ในกลุ่ม ("คุณสมบัติของกลุ่มซีรีส์").
"คุณสมบัติของกลุ่มซีรีส์" ในคลาส ChartSeriesGroup เป็นอ่าน/เขียน.
แต่ละ "คุณสมบัติของกลุ่มซีรีส์" สามารถมีการฉายเป็นแบบอ่านอย่างเดียวในคลาส ChartSeries.

### คำนิยาม:
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