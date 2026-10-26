---
title: Span
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: "แทนช่วงต่อเนื่องของหน่วยความจำใด ๆ ที่คล้ายกับ std::span ของ C++20."
type: docs
weight: 1262
url: /th/system/span/
---
## คลาส Span

แทนช่วงต่อเนื่องของหน่วยความจำใด ๆ ที่คล้ายกับ std::span ของ C++20

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span. คลาสนี้ให้วิธีการทำงานที่ปลอดภัยต่อประเภทเพื่อทำงานกับลำดับต่อเนื่องของอ็อบเจ็กต์. สามารถใช้ห่อหุ้มอาเรย์, อาเรย์สแต็ก, หรือพอยน์เตอร์ดิบพร้อมการตรวจสอบขอบเขต. [Span](./) ไม่ได้เป็นเจ้าของหน่วยความจำที่มันชี้ไป - มันเป็นเพียงมุมมองของหน่วยความจำที่มีอยู่ |

## เมธอด

| Method | Description |
| --- | --- |
| void [Clear](./clear/)() const | ล้างเนื้อหาของ span โดยตั้งค่าทุกองค์ประกอบเป็นค่าเริ่มต้น |
| void [Fill](./fill/)(const T\&) const | เติมค่าให้ span ด้วยค่าที่ระบุ |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | แปลงอาเรย์เป็น [Span](./) |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)