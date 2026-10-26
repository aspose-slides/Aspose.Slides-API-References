---
title: separator property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## คุณสมบัติ Separator
กำหนดหรือส่งคืน Variant ที่เป็นตัวแทนของตัวคั่นที่ใช้สำหรับป้ายข้อมูลบนแผนภูมิ
            อ่าน/เขียน **str**.


### หมายเหตุ

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the Separator property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the Separator property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.Separator = val;" cause to 
            all DataLabels[i].Separator is equal to val).

### คำจำกัดความ:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```


### ดูเพิ่มเติม
* คลาส [`IDataLabelFormat`](/slides/python-net/th/aspose.slides.charts/idatalabelformat)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)