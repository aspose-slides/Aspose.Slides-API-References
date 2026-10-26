---
title: RoundImpl()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ปัดเศษค่าที่ระบุให้เป็นค่าที่ใกล้ที่สุดโดยใช้จำนวนตำแหน่งทศนิยมตามที่กำหนด พารามิเตอร์หนึ่งระบุพฤติกรรมของฟังก์ชัน หากค่าที่ระบุอยู่ห่างเท่ากันจากสองจำนวนที่ใกล้ที่สุด
type: docs
weight: 287
url: /th/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) เมธอด

Rounds the specified value to the nearest value with the specified number of fractional digits. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **float** | ค่า value ที่จะปัดเศษ |
| digits | int | จำนวนตัวเลขทศนิยมในค่า value ที่ถูกปัดเศษ |
| mode | [MidpointRounding](../../midpointrounding/) | ระบุวิธีการทำการปัดเศษหาก **value** อยู่ห่างเท่ากันจากสองจำนวนที่ใกล้ที่สุด |

### Return Value

จำนวนที่มีจำนวนตัวเลขตามที่ระบุที่ใกล้ที่สุดกับ **value**

## See Also

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)