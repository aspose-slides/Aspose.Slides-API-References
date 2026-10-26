---
title: show_category_name property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name คุณสมบัติ
เป็นตัวแทนของพฤติกรรมการแสดงชื่อหมวดหมู่ของป้ายข้อมูลในแผนภูมที่ระบุ
            True เพื่อแสดงชื่อหมวดหมู่สำหรับป้ายข้อมูลบนแผนภูมิ. False เพื่อซ่อน.
            อ่าน/เขียน **bool**.


### หมายเหตุ

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowCategoryName property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowCategoryName property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" cause to 
            all DataLabels[i].ShowCategoryName is equal to val).

### คำนิยาม:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```


### ดูเพิ่มเติม
* คลาส [`IDataLabelFormat`](/slides/python-net/th/aspose.slides.charts/idatalabelformat)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)