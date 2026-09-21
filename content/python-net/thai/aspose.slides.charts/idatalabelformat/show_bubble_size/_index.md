---
title: show_bubble_size property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/idatalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size คุณสมบัติ
Represents a specified chart's data label bubble size value display behavior. 
True displays the bubble size value. False to hide.
อ่าน/เขียน **bool**.

### หมายเหตุ

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
property gets or sets the default value of the ShowBubbleSize property for the new data 
labels in the DataLabelCollection collection.
Set this property with value also sets this value to the ShowBubbleSize property 
for all data labels in the DataLabelCollection collection
(i.e. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" cause to 
all DataLabels[i].ShowBubbleSize is equal to val).

### คำจำกัดความ:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```

### ดูเพิ่มเติม
* คลาส [`IDataLabelFormat`](/slides/python-net/th/aspose.slides.charts/idatalabelformat)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)