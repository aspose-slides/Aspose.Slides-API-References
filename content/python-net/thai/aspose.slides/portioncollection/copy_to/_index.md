---
title: copy_to method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
คัดลอกองค์ประกอบของ **System.Collections.Generic.ICollection`1** ไปยัง **System.Array**, โดยเริ่มที่ตำแหน่ง **System.Array** ที่ระบุ

```python
def copy_to(self, array, array_index):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| array | **List[IPortion]** | อาร์เรย์ **System.Array** แบบมิติเดียวที่เป็นปลายทางขององค์ประกอบที่คัดลอกจาก **System.Collections.Generic.ICollection`1**. **System.Array** ต้องมีการจัดทำดัชนีแบบศูนย์ฐาน. |
| array_index | **int** | ดัชนีแบบศูนย์ฐานใน `array` ที่การคัดลอกเริ่มต้น. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` เป็นค่า None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` มีค่าต่ำกว่า 0. |
| **RuntimeError(Proxy error(ArgumentException))** | จำนวนขององค์ประกอบใน **System.Collections.Generic.ICollection`1** แหล่งที่มามากกว่าพื้นที่ว่างที่มีจาก `array_index` ถึงจุดสิ้นสุดของ `array` ปลายทาง. |



### ดูเพิ่มเติม
* คลาส [`PortionCollection`](/slides/python-net/th/aspose.slides/portioncollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)