---
title: show_leader_lines property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API อ้างอิง
description: 
type: docs
url: /th/aspose.slides.charts/datalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines คุณสมบัติ
Represents a specified chart's data label leader lines display behavior. 
            True displays the leader lines. False to hide.
            อ่าน/เขียน **bool**.


### หมายเหตุ

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowLeaderLines property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowLeaderLines property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" cause to 
            all DataLabels[i].ShowLeaderLines is equal to val).

### คำนิยาม:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```


### ดูเพิ่มเติม
* คลาส [`DataLabelFormat`](/slides/python-net/th/aspose.slides.charts/datalabelformat)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)