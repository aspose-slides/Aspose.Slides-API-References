---
title: MathF
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ประกอบด้วยฟังก์ชันคณิตศาสตร์สำหรับค่าแบบ floating-point ความแม่นยำเดี่ยว ซึ่งเป็นประเภท static ที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใด ๆ
type: docs
weight: 1795
url: /th/system/mathf/
---
## MathF struct

มีฟังก์ชันคณิตศาสตร์สำหรับค่าแบบ floating-point ความแม่นยำเดี่ยว ซึ่งเป็นประเภท static ที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใด ๆ

```cpp
class MathF
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| static T [Abs](./abs/)(T) | ส่งค่าตัวเลขสัมบูรณ์ของค่าที่ระบุ |
| static **float** [Acos](./acos/)(**float**) | คำนวณ arccosine ของค่าที่ระบุ |
| static **float** [Asin](./asin/)(**float**) | คำนวณ arcsin ของค่าที่ระบุ |
| static **float** [Atan](./atan/)(**float**) | คำนวณ arctan ของค่าที่ระบุ |
| static **float** [Atan2](./atan2/)(**float**, **float**) | คำนวณ arctan ของอัตราส่วนของค่าที่ระบุ |
| static **float** [Ceiling](./ceiling/)(**float**) | ส่งค่าจำนวนเต็มที่เล็กที่สุดที่มากกว่าหรือเท่ากับค่าที่ระบุ |
| static **float** [Cos](./cos/)(**float**) | คำนวณ cosine ของค่าที่ระบุ |
| static **float** [Cosh](./cosh/)(**float**) | คำนวณ hyperbolic cosine ของค่าที่ระบุ |
| static **float** [Exp](./exp/)(**float**) | ส่งค่าคงที่ e ที่ยกกำลังตามค่าที่ระบุ |
| static **float** [Floor](./floor/)(**float**) | ส่งค่าจำนวนเต็มที่ใหญ่ที่สุดที่น้อยกว่าหรือเท่ากับค่าที่ระบุ |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | ส่งค่าเศษที่ได้จากการหารของจำนวนที่ระบุด้วยอีกจำนวนที่ระบุ |
| static **float** [Log](./log/)(**float**) | ส่งค่าลอการิทึมธรรมชาติของค่าที่ระบุ |
| static **float** [Log](./log/)(**float**, **float**) | ส่งค่าลอการิทึมของค่าที่ระบุในฐานที่ระบุ |
| static **float** [Log10](./log10/)(**float**) | ส่งค่าลอการิทึมฐาน 10 ของค่าที่ระบุ |
| static **float** [Pow](./pow/)(**float**, **float**) | ส่งค่าที่ระบุที่ยกกำลังตามค่าที่ระบุ |
| static **float** [Round](./round/)(**float**) | ปัดค่าที่ระบุเป็นค่าจำนวนเต็มที่ใกล้ที่สุด |
| static **float** [Round](./round/)(**float**, int) | ปัดค่าที่ระบุเป็นค่าที่ใกล้ที่สุดโดยมีจำนวนตำแหน่งทศนิยมตามที่ระบุ |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | ปัดค่าที่ระบุเป็นจำนวนเต็มที่ใกล้ที่สุด พารามิเตอร์ระบุพฤติกรรมของฟังก์ชันหากค่าที่ระบุอยู่ห่างเท่ากันจากสองจำนวนที่ใกล้ที่สุด |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | ปัดค่าที่ระบุเป็นค่าที่ใกล้ที่สุดโดยมีจำนวนตำแหน่งทศนิยมตามที่ระบุ พารามิเตอร์ระบุพฤติกรรมของฟังก์ชันหากค่าที่ระบุอยู่ห่างเท่ากันจากสองจำนวนที่ใกล้ที่สุด |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | ปัดค่าที่ระบุเป็นค่าที่ใกล้ที่สุดโดยมีจำนวนตำแหน่งทศนิยมตามที่ระบุ พารามิเตอร์ระบุพฤติกรรมของฟังก์ชันหากค่าที่ระบุอยู่ห่างเท่ากันจากสองจำนวนที่ใกล้ที่สุด |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | กำหนดเครื่องหมายของค่าจำนวนเต็มที่มีเครื่องหมาย (signed) ที่ระบุ |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | กำหนดเครื่องหมายของค่าที่เป็น floating-point ที่ระบุ |
| static **float** [Sin](./sin/)(**float**) | คำนวณ sine ของค่าที่ระบุ |
| static **float** [Sinh](./sinh/)(**float**) | คำนวณ hyperbolic sine ของค่าที่ระบุ |
| static **float** [Sqrt](./sqrt/)(**float**) | ส่งค่ารากที่สองของค่าที่ระบุ |
| static **float** [Tan](./tan/)(**float**) | คำนวณ tangent ของค่าที่ระบุ |
| static **float** [Tanh](./tanh/)(**float**) | คำนวณ hyperbolic tangent ของค่าที่ระบุ |
| static **float** [Truncate](./truncate/)(**float**) | ส่งค่าประเภท floating point ความแม่นยำ float ที่มีส่วนจำนวนเต็มเท่ากับส่วนของค่าที่ระบุ โดยละทิ้งตำแหน่งทศนิยมทั้งหมด |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [E](./e/) | ฐานของลอการิทึมธรรมชาติ |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | ค่าคงที่ Pi |
| static [Tau](./tau/) | ค่า Tau |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)