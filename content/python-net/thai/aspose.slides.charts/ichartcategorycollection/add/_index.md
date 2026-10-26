---
title: add method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
หากประเภทมีอยู่ในคอลเลกชัน จะคืนค่ามัน มิฉะนั้นจะสร้างประเภทแผนภูมิใหม่จาก 
            [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell) และเพิ่มลงในคอลเลกชัน.

### ผลลัพธ์

ประเภทที่เพิ่มหรือที่มีอยู่แล้ว.



```python
def add(self, chart_data_cell):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell) | เซลล์ที่ใช้สร้างประเภทแผนภูมิ. |


## add(self, value) {#any}
สร้าง [`IChartCategory`](/slides/python-net/th/aspose.slides.charts/ichartcategory) ใหม่จากค่าและเพิ่มลงในคอลเลกชัน.

### ผลลัพธ์

เพิ่ม [`IChartCategory`](/slides/python-net/th/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| value | **any** | ค่าที่กำหนด. |

### หมายเหตุ

เมธอดนี้เพิ่ม worksheet ที่มีชื่อ AUTO_DATA และเพิ่มค่าทั้งหมดที่นั่น หากคุณใช้ [`IChartDataWorkbook`](/slides/python-net/th/aspose.slides.charts/ichartdataworkbook) เพื่อเพิ่มหรือแก้ไขค่าของเซลล์ โปรดแน่ใจว่าคุณจะไม่ใช้ worksheet นี้
            จำนวนค่าสูงสุดที่สามารถเพิ่มโดยใช้เมธอดนี้ต้องไม่เกิน 16711680

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | หากเกินขีดจำกัด |



### ดูเพิ่มเติม
* คลาส [`IChartCategory`](/slides/python-net/th/aspose.slides.charts/ichartcategory)
* คลาส [`IChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/ichartcategorycollection)
* คลาส [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell)
* คลาส [`IChartDataWorkbook`](/slides/python-net/th/aspose.slides.charts/ichartdataworkbook)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)