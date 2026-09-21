---
title: set_range method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/ichartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
ตั้งค่าช่วงข้อมูลของแผนภูมิ ซีรีส์และประเภทจะถูกอัปเดตตามช่วงข้อมูลใหม่.
หากจำนวนซีรีส์ในช่วงข้อมูลมากกว่าจำนวนซีรีส์ในข้อมูลของแผนภูมิ จะมีการเพิ่มซีรีส์เพิ่มเติมที่มีประเภทเดียวกับซีรีส์สุดท้ายในคอลเลกชันปัจจุบันไปยังส่วนท้ายของคอลเลกชัน.


```python
def set_range(self, formula):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| formula | **str** | สูตรช่วงข้อมูลของเซลล์ ตัวอย่างเช่น: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### ข้อยกเว้น

| ข้อยกเว้น | รายละเอียด |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula เป็นค่า None. |
| **RuntimeError(Proxy error(ArgumentException))** | formula มีรูปแบบที่ไม่ถูกต้อง. |



### ดูเพิ่มเติม
* คลาส [`IChartData`](/slides/python-net/th/aspose.slides.charts/ichartdata)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)