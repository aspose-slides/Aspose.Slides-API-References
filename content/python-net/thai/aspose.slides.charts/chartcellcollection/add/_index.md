---
title: add method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
เพิ่มเซลล์ใหม่เข้าไปในคอลเลกชัน.

```python
def add(self, cell):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell) | เซลล์ใหม่ที่จะเพิ่ม. |

## add(self, value) {#any}
สร้าง [`ChartDataCell`](/slides/python-net/th/aspose.slides.charts/chartdatacell) จากค่าที่ระบุและเพิ่มเข้าไปในคอลเลกชัน.

```python
def add(self, value):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| value | **any** | ค่า. |

### หมายเหตุ

เมธอดนี้เพิ่ม Worksheet ชื่อ AUTO_DATA และเพิ่มค่าทั้งหมดลงในนั้น หากคุณใช้ [`ChartDataWorkbook`](/slides/python-net/th/aspose.slides.charts/chartdataworkbook) เพื่อเพิ่มหรือแก้ไขค่าของเซลล์ ให้แน่ใจว่าคุณไม่ได้ใช้ Worksheet นี้
จำนวนค่าสูงสุดที่เพิ่มโดยเมธอดนี้ต้องไม่เกิน 16711680

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | หากเกินขีดจำกัด |

### ดูเพิ่มเติม
* คลาส [`ChartCellCollection`](/slides/python-net/th/aspose.slides.charts/chartcellcollection)
* คลาส [`ChartDataCell`](/slides/python-net/th/aspose.slides.charts/chartdatacell)
* คลาส [`ChartDataWorkbook`](/slides/python-net/th/aspose.slides.charts/chartdataworkbook)
* คลาส [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)