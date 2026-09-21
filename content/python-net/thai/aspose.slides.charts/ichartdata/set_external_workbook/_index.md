---
title: set_external_workbook method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ ข้อมูลแผนภูมิจะถูกอัปเดตจาก workbook เป้าหมาย


```python
def set_external_workbook(self, workbook_path):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| workbook_path | **str** | เส้นทางไปยัง workbook เป้าหมาย |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Workbook ภายนอกไม่พร้อมใช้งานหรือไม่สามารถโหลดได้. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| workbook_path | **str** | เส้นทางไปยัง workbook เป้าหมาย |
| update_chart_data | **bool** | หากค่าเป็น false จะอัปเดตเฉพาะเส้นทาง workbook เท่านั้น.<br/><br/>             ข้อมูลแผนภูมิจะไม่ถูกโหลดและอัปเดตจาก workbook เป้าหมาย สามารถใช้ได้เมื่อ workbook เป้าหมายไม่มีอยู่หรือไม่พร้อมใช้งาน.<br/><br/>             หากค่าเป็น true ข้อมูลแผนภูมิจะถูกอัปเดตจาก workbook เป้าหมาย. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Workbook ภายนอกไม่พร้อมใช้งานหรือไม่สามารถโหลดได้. |



### ดูเพิ่มเติม
* คลาส [`IChartData`](/slides/python-net/th/aspose.slides.charts/ichartdata)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)