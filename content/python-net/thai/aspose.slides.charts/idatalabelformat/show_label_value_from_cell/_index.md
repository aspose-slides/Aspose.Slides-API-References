---
title: show_label_value_from_cell property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell property
เป็นการแทนพฤติกรรมการแสดงค่าของเซลล์ป้ายข้อมูลในแผนภูมิที่ระบุ  
True แสดงค่าเซลล์. False ซ่อนค่า.  
อ่าน/เขียน **bool**.

### Remarks
หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้ว คุณสมบัตินี้จะรับหรือกำหนดค่าพื้นฐานของคุณสมบัติ ShowLabelValueFromCell สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection. การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งยังจะตั้งค่าค่านั้นให้กับคุณสมบัติ ShowLabelValueFromCell สำหรับป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection (เช่น "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" ทำให้ทุก DataLabels[i].ShowLabelValueFromCell มีค่าเท่ากับ val).

### คำนิยาม:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```

### See Also
* คลาส [`IDataLabelFormat`](/slides/python-net/th/aspose.slides.charts/idatalabelformat)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)