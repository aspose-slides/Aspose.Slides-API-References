---
title: set_range method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
ตั้งค่าช่วงข้อมูลของแผนภูมิ ชุดข้อมูลและประเภทจะถูกอัปเดตตามช่วงข้อมูลใหม่.
            หากจำนวนชุดข้อมูลในช่วงข้อมูลมากกว่าจำนวนชุดข้อมูลในแผนภูมิ จะมีการเพิ่มชุดข้อมูลเพิ่มเติมที่มีประเภทเดียวกับชุดข้อมูลสุดท้ายในชุดปัจจุบันที่ส่วนท้ายของชุดข้อมูล.

```python
def set_range(self, formula):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| formula | **str** | สูตรช่วงข้อมูลของเซลล์ เช่น: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula เป็น None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | ชนิดแผนภูมิที่ไม่รองรับ |
| **RuntimeError(Proxy error(ArgumentException))** | สูตรมีรูปแบบไม่ถูกต้อง. |

### ดูเพิ่มเติม
* คลาส [`ChartData`](/slides/python-net/th/aspose.slides.charts/chartdata)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)