---
title: add method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
เพิ่มเซลล์ใหม่ลงในคอลเลกชัน.

```python
def add(self, chart_data_cell):
    ...
```

| พารามิเตอร์ | ชนิด | รายละเอียด |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell) | เซลล์ใหม่ที่จะเพิ่ม. |

## add(self, value) {#any}
สร้าง [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell) จากค่าที่ระบุและเพิ่มลงในคอลเลกชัน.

```python
def add(self, value):
    ...
```

| พารามิเตอร์ | ชนิด | รายละเอียด |
| :- | :- | :- |
| value | **any** | ค่า. |

### หมายเหตุ
เมธอดนี้เพิ่มแผ่นงานที่มีชื่อ AUTO_DATA และเพิ่มค่าทั้งหมดลงในนั้น หากคุณใช้ [`IChartDataWorkbook`](/slides/python-net/th/aspose.slides.charts/ichartdataworkbook) เพื่อเพิ่มหรือแก้ไขค่า Cell โปรดแน่ใจว่าไม่ได้ใช้แผ่นงานนี้
จำนวนค่าสูงสุดที่เพิ่มโดยใช้เมธอดนี้ต้องไม่เกิน 16711680

### ข้อยกเว้น

| ข้อยกเว้น | รายละเอียด |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | หากเกินขีดจำกัด |

### ดูเพิ่มเติม
* คลาส [`IChartCellCollection`](/slides/python-net/th/aspose.slides.charts/ichartcellcollection)
* คลาส [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell)
* คลาส [`IChartDataWorkbook`](/slides/python-net/th/aspose.slides.charts/ichartdataworkbook)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)