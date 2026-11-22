---
title: set_range method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/ichartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
ตั้งค่าช่วงข้อมูลของแผนภูมิ ซีรีส์และหมวดหมู่จะอัปเดตตามช่วงข้อมูลใหม่.
            หากจำนวนซีรีส์ในช่วงข้อมูลมากกว่าจำนวนซีรีส์ในข้อมูลของแผนภูมิ
            จะมีการเพิ่มซีรีส์เพิ่มเติมที่มีประเภทเดียวกับซีรีส์สุดท้ายในคอลเลกชันปัจจุบันไปที่ส่วนท้ายของคอลเลกชัน.


```python
def set_range(self, formula):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| formula | **str** | สูตรช่วงข้อมูลของเซลล์ ตัวอย่าง: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula เป็น None. |
| **RuntimeError(Proxy error(ArgumentException))** | formula มีรูปแบบไม่ถูกต้อง. |



### See Also
* คลาส [`IChartData`](/slides/python-net/th/aspose.slides.charts/ichartdata)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)