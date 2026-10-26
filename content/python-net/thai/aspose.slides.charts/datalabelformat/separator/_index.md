---
title: separator property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## คุณสมบัติตัวคั่น
กำหนดหรือคืนค่า Variant ที่แสดงถึงตัวคั่นที่ใช้สำหรับป้ายกำกับข้อมูลบนแผนภูมิ
            อ่าน/เขียน **str**.

### หมายเหตุ

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            คุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ Separator สำหรับป้ายกำกับข้อมูลใหม่ในคอลเลกชัน DataLabelCollection
            การตั้งค่าคุณสมบัตินี้ด้วยค่าใดค่าหนึ่งจะกำหนดค่านั้นให้กับคุณสมบัติ Separator สำหรับป้ายกำกับข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection
            (เช่น "DataLabels.DefaultDataLabelFormat.Separator = val;" ทำให้ทุก DataLabels[i].Separator มีค่าเท่ากับ val).

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
* คลาส [`DataLabelFormat`](/slides/python-net/th/aspose.slides.charts/datalabelformat)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)