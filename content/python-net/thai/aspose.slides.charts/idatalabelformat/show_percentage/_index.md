---
title: show_percentage property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/idatalabelformat/show_percentage/
weight: 180
---
## show_percentage คุณสมบัติ
แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลของแผนภูมิที่ระบุ  
True แสดงค่าร้อยละ. False เพื่อซ่อน.  
อ่าน/เขียน **bool**.

### หมายเหตุ

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowPercentage property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowPercentage property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" cause to 
            all DataLabels[i].ShowPercentage is equal to val).

### คำจำกัดความ:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```

### ดูเพิ่มเติม
* คลาส [`IDataLabelFormat`](/slides/python-net/th/aspose.slides.charts/idatalabelformat)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)