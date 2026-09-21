---
title: insert_chart method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/shapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
สร้างแผนภูมิใหม่ เริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า แล้วแทรกเข้าไปในคอลเลกชันรูปทรงที่ดัชนีที่ระบุ

### Returns

ออบเจ็กต์ที่สร้างใหม่ [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype) | ประเภทของแผนภูมิที่จะสร้าง |
| x | **float** | พิกัด x ของแผนภูมิใหม่ หน่วยเป็นพ้อยท์ |
| y | **float** | พิกัด y ของแผนภูมิใหม่ หน่วยเป็นพ้อยท์ |
| width | **float** | ความกว้างของแผนภูมิใหม่ หน่วยเป็นพ้อยท์ |
| height | **float** | ความสูงของแผนภูมิใหม่ หน่วยเป็นพ้อยท์ |
| index | **int** | ดัชนีฐานศูนย์ที่ต้องการแทรกแผนภูมิใหม่ในคอลเลกชันรูปทรง |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
สร้างแผนภูมิใหม่ เริ่มต้นด้วยข้อมูลชุดตัวอย่างและการตั้งค่า แล้วแทรกเข้าไปในคอลเลกชันรูปทรงที่ดัชนีที่ระบุ

### Returns

ออบเจ็กต์ที่สร้างใหม่ [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype) | ประเภทของแผนภูมิที่จะสร้าง |
| x | **float** | พิกัด x ของแผนภูมิใหม่ หน่วยเป็นพ้อยท์ |
| y | **float** | พิกัด y ของแผนภูมิใหม่ หน่วยเป็นพ้อยท์ |
| width | **float** | ความกว้างของแผนภูมิใหม่ หน่วยเป็นพ้อยท์ |
| height | **float** | ความสูงของแผนภูมิใหม่ หน่วยเป็นพ้อยท์ |
| index | **int** | ดัชนีฐานศูนย์ที่ต้องการแทรกแผนภูมิใหม่ในคอลเลกชันรูปทรง |
| init_with_sample | **bool** | True เพื่อเริ่มต้นแผนภูมิใหม่ด้วยข้อมูลชุดตัวอย่างและการตั้งค่า; false เพื่อสร้างแผนภูมิโดยไม่มีชุดข้อมูลและเพียงการตั้งคือน้อยที่สุด ซึ่งทำให้การสร้างเร็วขึ้น |



### See Also
* enumeration [`ChartType`](/slides/python-net/th/aspose.slides.charts/charttype)
* class [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart)
* class [`ShapeCollection`](/slides/python-net/th/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)