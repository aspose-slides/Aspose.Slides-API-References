---
title: show_value property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value คุณสมบัติ
เป็นตัวแทนพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. 
            True แสดงค่าร้อยละ. False เพื่อซ่อน.
            อ่าน/เขียน **bool**.


### หมายเหตุ

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowValue Property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowValue property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" cause to 
            all DataLabels[i].ShowValue is equal to val).

### การกำหนด:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```


### ดูเพิ่มเติม
* คลาส [`DataLabelFormat`](/slides/python-net/th/aspose.slides.charts/datalabelformat)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)