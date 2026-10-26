---
title: ReadOnlySpan
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ส่งต่อเพื่อใช้ภายในคลาส Span.
type: docs
weight: 1210
url: /th/system/readonlyspan/
---
## คลาส ReadOnlySpan

ส่งต่อเพื่อใช้ภายใน [Span](../span/) คลาส.

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน. คลาสนี้ให้วิธีที่ปลอดภัยตามประเภทเพื่อทำงานกับลำดับต่อเนื่องของวัตถุในรูปแบบอ่านอย่างเดียว. สามารถใช้ห่ออาเรย์, อาเรย์บนสแตก, หรือพอยน์เตอร์ดิบขณะยังคงตรวจสอบขอบเขต. [ReadOnlySpan](./) ไม่ได้เป็นเจ้าของหน่วยความจำที่มันชี้ไป - เป็นเพียงมุมมองของหน่วยความจำที่มีอยู่. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | สร้างสแปนอ่านอย่างเดียวจากสแปนทั่วไป. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | แปลงอาเรย์เป็น [ReadOnlySpan](./). |

## หมายเหตุ

แสดงถึงพื้นที่ต่อเนื่องแบบอ่านอย่างเดียวของหน่วยความจำแบบ任意.

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)