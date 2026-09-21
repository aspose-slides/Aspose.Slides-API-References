---
title: copy_to method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
คัดลอกอิงค์เมนต์ของ **System.Collections.Generic.ICollection`1** ไปยัง **System.Array** โดยเริ่มที่ดัชนีของ **System.Array** ที่ระบุ

```python
def copy_to(self, array, array_index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| array | **List[IParagraph]** | **System.Array** แบบมิติเดียวที่เป็นที่รับของอิงค์เมนต์ที่คัดลอกจาก **System.Collections.Generic.ICollection`1**. **System.Array** ต้องมีการจัดทำดัชนีแบบศูนย์ฐาน. |
| array_index | **int** | ดัชนีศูนย์ฐานใน `array` ที่การคัดลอกเริ่มต้น. |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` เป็น None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` น้อยกว่า 0. |
| **RuntimeError(Proxy error(ArgumentException))** | จำนวนอิงค์เมนต์ในแหล่งที่มาของ **System.Collections.Generic.ICollection`1** มากกว่าพื้นที่ว่างที่มีจาก `array_index` ถึงจุดสิ้นสุดของ `array` ที่เป็นปลายทาง. |

### ดูเพิ่มเติม
* คลาส [`ParagraphCollection`](/slides/python-net/th/aspose.slides/paragraphcollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)