---
title: Math
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: มีฟังก์ชันคณิตศาสตร์ ประเภทนี้เป็นประเภท static ที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใดๆ
type: docs
weight: 1782
url: /th/system/math/
---
## Math struct

มีฟังก์ชันคณิตศาสตร์ ประเภทนี้เป็นประเภท static ที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใดๆ

```cpp
class Math
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static T [Abs](./abs/)(T) | คืนค่าค่าสัมบูรณ์ของค่าเฉพาะที่ระบุ |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | คืนค่าค่าสัมบูรณ์ของค่าที่แสดงโดยอ็อบเจกต์ [Decimal](../decimal/) ที่ระบุ |
| static **double** [Acos](./acos/)(**double**) | คำนวณค่า arccosine ของค่าที่ระบุ |
| static **double** [Asin](./asin/)(**double**) | คำนวณค่า arcsin ของค่าที่ระบุ |
| static **double** [Atan](./atan/)(**double**) | คำนวณค่า arctan ของค่าที่ระบุ |
| static **double** [Atan2](./atan2/)(**double**, **double**) | คำนวณค่า arctan ของอัตราส่วนของค่าที่ระบุ |
| static **int64_t** [BigMul](./bigmul/)(int, int) | คืนค่าผลคูณเต็มของสองจำนวนเต็ม 32-bit |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | คืนค่าจำนวนเต็มที่เล็กที่สุดที่มากกว่าหรือเท่ากับค่าที่ระบุ |
| static **double** [Ceiling](./ceiling/)(**double**) | คืนค่าจำนวนเต็มที่เล็กที่สุดที่มากกว่าหรือเท่ากับค่าที่ระบุ |
| static **double** [Cos](./cos/)(**double**) | คำนวณค่า cosine ของค่าที่ระบุ |
| static **double** [Cosh](./cosh/)(**double**) | คำนวณค่า hyperbolic cosine ของค่าที่ระบุ |
| static int [DivRem](./divrem/)(int, int, int\&) | คำนวณผลหารของสองจำนวนเต็ม 32-bit และเศษ |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | คำนวณผลหารของสองจำนวนเต็ม 64-bit และเศษ |
| static **double** [Exp](./exp/)(**double**) | คืนค่าคงที่ e ที่ยกกำลังตามค่าเฉพาะที่ระบุ |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | คืนค่าจำนวนเต็มที่ใหญ่ที่สุดที่น้อยกว่าหรือเท่ากับค่าที่ระบุ |
| static **double** [Floor](./floor/)(**double**) | คืนค่าจำนวนเต็มที่ใหญ่ที่สุดที่น้อยกว่าหรือเท่ากับค่าที่ระบุ |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | คืนค่าเศษที่เกิดจากการหารของจำนวนที่ระบุหนึ่งด้วยจำนวนที่ระบุอีกจำนวนหนึ่ง |
| static **double** [Log](./log/)(**double**) | คืนค่าลอการิทึมธรรมชาติของค่าที่ระบุ |
| static **double** [Log](./log/)(**double**, **double**) | คืนค่าลอการิทึมของค่าที่ระบุในฐานที่ระบุ |
| static **double** [Log10](./log10/)(**double**) | คืนค่าลอการิทึมฐาน 10 ของค่าที่ระบุ |
| static auto [Max](./max/)(T0, T1) | คืนค่ามากที่สุดจากสองค่าตัวเลขที่ระบุ |
| static T0 [Max](./max/)(T0, T1) | คืนค่ามากที่สุดจากสองค่าตัวเลขที่ระบุ |
| **float** [Max_](./max_/)(**float**, **float**) | คืนค่าจุดลอยเดี่ยวความแม่นยำหนึ่งที่ใหญ่ที่สุดจากสองค่าที่ระบุ |
| **double** [Max_](./max_/)(**double**, **double**) | คืนค่าจุดลอยความแม่นยำคู่ที่ใหญ่ที่สุดจากสองค่าที่ระบุ |
| static auto [Min](./min/)(T0, T1) | คืนค่าที่เล็กที่สุดจากสองค่าตัวเลขที่ระบุ |
| static T0 [Min](./min/)(T0, T1) | คืนค่าที่เล็กที่สุดจากสองค่าตัวเลขที่ระบุ |
| **float** [Min_](./min_/)(**float**, **float**) | คืนค่าจุดลอยเดี่ยวความแม่นยำหนึ่งที่เล็กที่สุดจากสองค่าที่ระบุ |
| **double** [Min_](./min_/)(**double**, **double**) | คืนค่าจุดลอยความแม่นยำคู่ที่เล็กที่สุดจากสองค่าที่ระบุ |
| static T [Modulus](./modulus/)(T, T) | คำนวณค่าเศษที่เกิดจากการหารค่าที่ระบุหนึ่งด้วยค่าที่ระบุอีกค่า |
| static **double** [Pow](./pow/)(**double**, **double**) | คืนค่าที่ระบุยกกำลังตามค่าที่ระบุ |
| static **double** [Round](./round/)(**double**) | ปัดค่าที่ระบุให้เป็นค่าจำนวนเต็มที่ใกล้ที่สุด |
| static **double** [Round](./round/)(**double**, int) | ปัดค่าที่ระบุให้เป็นค่าที่ใกล้ที่สุดโดยมีจำนวนตำแหน่งทศนิยมตามที่ระบุ |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | ปัดค่าที่ระบุให้เป็นจำนวนจำนวนเต็มที่ใกล้ที่สุด พารามิเตอร์ระบุพฤติกรรมของฟังก์ชันหากค่าที่ระบุเท่ากันกับระยะห่างจากสองจำนวนที่ใกล้ที่สุด |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | ปัดค่าที่ระบุให้เป็นค่าที่ใกล้ที่สุดโดยมีจำนวนตำแหน่งทศนิยมตามที่ระบุ พารามิเตอร์ระบุพฤติกรรมของฟังก์ชันหากค่าที่ระบุเท่ากันกับระยะห่างจากสองจำนวนที่ใกล้ที่สุด |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | ปัดค่าที่ระบุให้เป็นค่าจำนวนเต็มที่ใกล้ที่สุด |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | ปัดค่าที่ระบุให้เป็นค่าที่ใกล้ที่สุดโดยมีจำนวนตำแหน่งทศนิยมตามที่ระบุ |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | ปัดค่าที่ระบุให้เป็นจำนวนจำนวนเต็มที่ใกล้ที่สุด พารามิเตอร์ระบุพฤติกรรมของฟังก์ชันหากค่าที่ระบุเท่ากันกับระยะห่างจากสองจำนวนที่ใกล้ที่สุด |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | ปัดค่าที่ระบุให้เป็นค่าที่ใกล้ที่สุดโดยมีจำนวนตำแหน่งทศนิยมตามที่ระบุ พารามิเตอร์ระบุพฤติกรรมของฟังก์ชันหากค่าที่ระบุเท่ากันกับระยะห่างจากสองจำนวนที่ใกล้ที่สุด |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | กำหนดเครื่องหมายของค่าจำนวนเต็มที่เป็น signed ตามที่ระบุ |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | กำหนดเครื่องหมายของค่าจุดลอยที่ระบุ |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | กำหนดเครื่องหมายของค่าทศนิยมที่ระบุ |
| static **double** [Sin](./sin/)(**double**) | คำนวณค่า sine ของค่าที่ระบุ |
| static **double** [Sinh](./sinh/)(**double**) | คำนวณค่า hyperbolic sine ของค่าที่ระบุ |
| static **double** [Sqrt](./sqrt/)(**double**) | คืนค่ารากที่สองของค่าที่ระบุ |
| static **double** [Tan](./tan/)(**double**) | คำนวณค่า tangent ของค่าที่ระบุ |
| static **double** [Tanh](./tanh/)(**double**) | คำนวณค่า hyperbolic tangent ของค่าที่ระบุ |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | คืนอ็อบเจกต์ [Decimal](../decimal/) ที่แสดงค่าที่มีส่วนเต็มเท่ากับส่วนเต็มของค่าที่แทนโดยอ็อบเจกต์ [Decimal](../decimal/) ที่ระบุ โดยลบตำแหน่งทศนิยมทั้งหมดออก |
| static **double** [Truncate](./truncate/)(**double**) | คืนค่าจุดลอยความแม่นยำคู่ที่มีส่วนเต็มเท่ากับส่วนเต็มของค่าที่ระบุ โดยลบตำแหน่งทศนิยมทั้งหมดออก |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [E](./e/) | ฐานของลอการิทึมธรรมชาติ |
| static [NaN](./nan/) | แทนค่าที่ไม่ใช่ตัวเลข (NaN) |
| static [NegativeInfinity](./negativeinfinity/) | แทนค่าจำกัดลบไม่สิ้นสุด |
| static [PI](./pi/) | ค่าคงที่ของจำนวน Pi |
| static [PositiveInfinity](./positiveinfinity/) | แทนค่าจำกัดบวกไม่สิ้นสุด |

## หมายเหตุ

```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // พิมพ์ค่าตัวเลขสัมบูรณ์.
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // พิมพ์ค่า sine ของ PI/2 และค่า cosine ของ PI.
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
ตัวอย่างโค้ดนี้สร้างผลลัพธ์ดังต่อไปนี้:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)