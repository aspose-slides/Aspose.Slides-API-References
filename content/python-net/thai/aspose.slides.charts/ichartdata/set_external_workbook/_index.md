---
title: set_external_workbook method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
กำหนดเวิร์กบุ๊กภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ ข้อมูลแผนภูมิจะได้รับการอัปเดตจากเวิร์กบุ๊กเป้าหมาย


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | เส้นทางไปยังเวิร์กบุ๊กเป้าหมาย |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | เวิร์กบุ๊กภายนอกไม่พร้อมใช้งานหรือไม่สามารถโหลดได้. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
กำหนดเวิร์กบุ๊กภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | เส้นทางไปยังเวิร์กบุ๊กเป้าหมาย |
| update_chart_data | **bool** | หากค่าเป็น false จะอัปเดตเฉพาะเส้นทางของเวิร์กบุ๊กเท่านั้น. <br/><br/>             ข้อมูลแผนภูมิจะไม่ถูกโหลดและอัปเดตจากเวิร์กบุ๊กเป้าหมาย สามารถใช้ได้เมื่อเวิร์กบุ๊กเป้าหมายไม่มีอยู่หรือไม่สามารถใช้งานได้.<br/><br/>             หากค่าเป็น true จะอัปเดตข้อมูลแผนภูมิกจากเวิร์กบุ๊กเป้าหมาย. |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | เวิร์กบุ๊กภายนอกไม่พร้อมใช้งานหรือไม่สามารถโหลดได้. |



### ดูเพิ่มเติม
* คลาส [`IChartData`](/slides/python-net/th/aspose.slides.charts/ichartdata)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)