---
title: number_format property
second_title: อ้างอิง API Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format คุณสมบัติ
แสดงถึงสตริงรูปแบบสำหรับอ็อบเจ็กต์ DataLabels.
            อ่าน/เขียน **str**.


### หมายเหตุ

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this
            คุณสมบัตินี้จะรับหรือกำหนดค่าเริ่มต้นของคุณสมบัติ NumberFormat สำหรับป้ายกำกับข้อมูลใหม่ในคอลเลกชัน DataLabelCollection
            เมื่อคุณสมบัตินี้ถูกตั้งค่าเป็นค่าหนึ่ง ค่านั้นจะถูกตั้งค่าสำหรับคุณสมบัติ NumberFormat ของป้ายกำกับข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection ด้วย (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" ทำให้ DataLabels[i].NumberFormat ทั้งหมดเท่ากับ val).

### คำนิยาม:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### ดูเพิ่มเติม
* คลาส [`IDataLabelFormat`](/slides/python-net/th/aspose.slides.charts/idatalabelformat)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)