---
title: show_category_name property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name คุณสมบัติ
แสดงถึงพฤติกรรมการแสดงชื่อหมวดหมู่ของป้ายข้อมูลในแผนภูมิที่กำหนด.
            True เพื่อแสดงชื่อหมวดหมู่สำหรับป้ายข้อมูลบนแผนภูมิ. False เพื่อซ่อน.
            อ่าน/เขียน **bool**.

### หมายเหตุ

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowCategoryName property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowCategoryName property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" ทำให้ DataLabels[i].ShowCategoryName ทั้งหมดเท่ากับ val.)

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
* คลาส [`DataLabelFormat`](/slides/python-net/th/aspose.slides.charts/datalabelformat)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)