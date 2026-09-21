---
title: delete_column method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
ลบคอลัมน์ที่ระบุ


```python
def delete_column(self, column_index):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| column_index | **int** | ดัชนีที่เริ่มจากศูนย์ของคอลัมน์ที่ต้องการลบ. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | เมื่อคุณพยายามลบคอลัมน์เดียวสุดท้ายในเมทริกซ์ |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | หาก columnIndex น้อยกว่าศูนย์หรือมากกว่าหรือเท่ากับ ColumnCount |



### ดูเพิ่มเติม
* คลาส [`MathMatrix`](/slides/python-net/th/aspose.slides.mathtext/mathmatrix)
* โมดูล [`aspose.slides.mathtext`](/slides/python-net/th/aspose.slides.mathtext)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)