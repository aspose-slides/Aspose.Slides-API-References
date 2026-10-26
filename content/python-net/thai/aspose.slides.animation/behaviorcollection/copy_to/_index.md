---
title: copy_to method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
คัดลอกองค์ประกอบจาก **System.Collections.Generic.ICollection`1** ไปยัง **System.Array** โดยเริ่มที่ดัชนีของ **System.Array** ที่ระบุ

```python
def copy_to(self, array, array_index):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| array | **List[IBehavior]** | **System.Array** แบบมิติเดียวที่เป็นจุดหมายขององค์ประกอบที่คัดลอกจาก **System.Collections.Generic.ICollection`1**. **System.Array** ต้องใช้การจัดทำดัชนีแบบศูนย์เริ่มต้น. |
| array_index | **int** | ดัชนีเริ่มต้นจากศูนย์ใน `array` ที่การคัดลอกรายการเริ่มต้น. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` มีค่าเป็น None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` มีค่าน้อยกว่า 0. |
| **RuntimeError(Proxy error(ArgumentException))** | จำนวนขององค์ประกอบใน **System.Collections.Generic.ICollection`1** แหล่งที่มามากกว่าพื้นที่ที่ว่างจาก `array_index` ไปจนถึงจุดสิ้นสุดของ `array` ที่เป็นจุดหมาย. |

### ดูเพิ่มเติม
* คลาส [`BehaviorCollection`](/slides/python-net/th/aspose.slides.animation/behaviorcollection)
* โมดูล [`aspose.slides.animation`](/slides/python-net/th/aspose.slides.animation)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)