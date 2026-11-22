---
title: set_range method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/chartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
ตั้งค่าช่วงข้อมูลของแผนภูมิ Series และ categories จะถูกอัปเดตตามช่วงข้อมูลใหม่
            หากจำนวน series ใน data range มากกว่าจำนวน series ใน chart data จะมีการเพิ่ม series เพิ่มเติมที่มีประเภทเดียวกันกับ series สุดท้ายใน collection ปัจจุบันที่ส่วนท้ายของ collection


```python
def set_range(self, formula):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| formula | **str** | สูตรช่วงข้อมูลเซลล์ ตัวอย่าง: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula เป็น None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | ประเภทแผนภูมิที่ไม่รองรับ |
| **RuntimeError(Proxy error(ArgumentException))** | formula มีรูปแบบไม่ถูกต้อง. |



### ดูเพิ่มเติม
* class [`ChartData`](/slides/python-net/th/aspose.slides.charts/chartdata)
* module [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)