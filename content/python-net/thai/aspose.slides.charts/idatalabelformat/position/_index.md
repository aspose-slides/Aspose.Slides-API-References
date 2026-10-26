---
title: position property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/idatalabelformat/position/
weight: 90
---
## คุณสมบัติ position
Represents the position of the data label.
            Read/write [`LegendDataLabelPosition`](/slides/python-net/th/aspose.slides.charts/legenddatalabelposition).

### หมายเหตุ

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the Position property for the new data 
            labels in the DataLabelCollection collection.
            Represents the position for the DataLabel objects.
            Set this property with value also sets this value to the Position property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.Position = val;" cause to 
            all DataLabels[i].Position is equal to val).

### คำนิยาม:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### ดูเพิ่มเติม
* คลาส [`IDataLabelFormat`](/slides/python-net/th/aspose.slides.charts/idatalabelformat)
* enum [`LegendDataLabelPosition`](/slides/python-net/th/aspose.slides.charts/legenddatalabelposition)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)