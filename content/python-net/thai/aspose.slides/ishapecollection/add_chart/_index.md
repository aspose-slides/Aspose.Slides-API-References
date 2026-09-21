---
title: add_chart method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ishapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลและการตั้งค่า series ตัวอย่าง, และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปร่าง.

### คืนค่า

อ็อบเจกต์ใหม่ที่สร้าง [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart).

```python
def add_chart(self, type, x, y, width, height):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype) | The type of chart to add. |
| x | **float** | The x-coordinate of the new chart, in points. |
| y | **float** | The y-coordinate of the new chart, in points. |
| width | **float** | The width of the chart, in points. |
| height | **float** | The height of the chart, in points. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
สร้างแผนภูมิใหม่, เริ่มต้นด้วยข้อมูลและการตั้งค่า series ตัวอย่าง, และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปร่าง.

### คืนค่า

อ็อบเจกต์ใหม่ที่สร้าง [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart).

```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype) | The type of chart to add. |
| x | **float** | The x-coordinate of the new chart, in points. |
| y | **float** | The y-coordinate of the new chart, in points. |
| width | **float** | The width of the chart, in points. |
| height | **float** | The height of the chart, in points. |
| init_with_sample | **bool** | True เพื่อเริ่มต้นแผนภูมิใหม่ด้วยข้อมูล series ตัวอย่างและการตั้งค่า; <br/><br/>            false เพื่อสร้างแผนภูมิโดยไม่มี series และมีการตั้งค่าน้อยที่สุด ซึ่งทำให้การสร้างเร็วขึ้น. |



### ดูเพิ่มเติม
* enumeration [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype)
* คลาส [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)