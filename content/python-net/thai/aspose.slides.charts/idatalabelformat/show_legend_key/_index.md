---
title: show_legend_key property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/idatalabelformat/show_legend_key/
weight: 170
---
## show_legend_key คุณสมบัติ
แสดงพฤติกรรมการแสดงคีย์ของป้ายข้อมูลในแผนภูมิที่ระบุ  
True หากคีย์ของป้ายข้อมูลแสดงผล  
อ่าน/เขียน **bool**.

### หมายเหตุ
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            คุณสมบัติจะรับหรือกำหนดค่ามาตรฐานของคุณสมบัติ ShowLegendKey สำหรับข้อมูลใหม่ 
            ป้ายในคอลเลกชัน DataLabelCollection.
            ตั้งค่าคุณสมบัตินี้ด้วยค่าเดียวกันยังตั้งค่านี้ให้กับคุณสมบัติ ShowLegendKey 
            สำหรับป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" ทำให้ 
            ทุก DataLabels[i].ShowLegendKey มีค่าเท่ากับ val).

### คำนิยาม:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### ดูเพิ่มเติม
* คลาส [`IDataLabelFormat`](/slides/python-net/th/aspose.slides.charts/idatalabelformat)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)