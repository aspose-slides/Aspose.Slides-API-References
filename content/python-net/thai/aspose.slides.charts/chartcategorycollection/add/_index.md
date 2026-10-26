---
title: add method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
หากหมวดหมู่มีอยู่ในคอลเล็กชัน จะส่งคืนค่านั้น หากไม่มี จะสร้างหมวดหมู่แผนภูมิใหม่จาก [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell) และเพิ่มลงในคอลเล็กชัน

### ผลลัพธ์

หมวดหมู่ที่เพิ่มหรือที่มีอยู่แล้ว



```python
def add(self, chart_data_cell):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell) | เซลล์ที่ใช้สร้างหมวดหมู่แผนภูมิ |


## add(self, value) {#any}
สร้าง [`ChartCategory`](/slides/python-net/th/aspose.slides.charts/chartcategory) ใหม่จากค่าและเพิ่มลงในคอลเล็กชัน

### ผลลัพธ์

เพิ่ม [`IChartCategory`](/slides/python-net/th/aspose.slides.charts/ichartcategory)



```python
def add(self, value):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| value | **any** | ค่าที่ให้มา |

### หมายเหตุ

เมธอดนี้เพิ่มแผ่นงานที่ชื่อ AUTO_DATA และเพิ่มค่าทั้งหมดลงในนั้น หากคุณใช้ [`ChartDataWorkbook`](/slides/python-net/th/aspose.slides.charts/chartdataworkbook) เพื่อเพิ่มหรือแก้ไขค่าของเซลล์ ให้แน่ใจว่าคุณไม่ได้ใช้แผ่นงานนี้
            จำนวนค่าที่เพิ่มโดยใช้เมธอดนี้ต้องไม่เกิน 16711680

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | หากเกินขีดจำกัด |



### ดูเพิ่มเติม
* คลาส [`ChartCategory`](/slides/python-net/th/aspose.slides.charts/chartcategory)
* คลาส [`ChartCategoryCollection`](/slides/python-net/th/aspose.slides.charts/chartcategorycollection)
* คลาส [`ChartDataWorkbook`](/slides/python-net/th/aspose.slides.charts/chartdataworkbook)
* คลาส [`IChartCategory`](/slides/python-net/th/aspose.slides.charts/ichartcategory)
* คลาส [`IChartDataCell`](/slides/python-net/th/aspose.slides.charts/ichartdatacell)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)