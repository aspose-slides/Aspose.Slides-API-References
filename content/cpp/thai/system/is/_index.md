---
title: Is()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ทำการแปลรูปแบบการประกาศ 'is'
type: docs
weight: 2302
url: /th/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) ฟังก์ชัน

ทำการแปลรูปแบบประกาศ 'is'.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```

### พารามิเตอร์แบบเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| PatternT | ประเภทที่จะตรวจสอบ. |
| ExpressionT | ประเภทของนิพจน์ซ้าย. |
| ResultT | ประเภทของนิพจน์ผลลัพธ์. |

### อาร์กูเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| left | const ExpressionT\& | นิพจน์ที่จะถูกตรวจสอบ. |
| result | ResultT\& | ตัวแปรที่จะได้รับการกำหนดให้เป็นประเภทที่ตรวจสอบแล้ว. |

### ค่าที่ส่งกลับ

true หากการตรวจสอบประเภทสำเร็จ, false หากไม่สำเร็จ.

## System::Is(const ExpressionT\&, const ConstantT\&) ฟังก์ชัน

ทำการแปลรูปแบบคอนสแตนต์ 'is'.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```

### พารามิเตอร์แบบเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ExpressionT | ประเภทของนิพจน์ซ้าย. |
| ConstantT | ประเภทของนิพจน์คอนสแตนต์. |

### อาร์กูเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| left | const ExpressionT\& | นิพจน์ที่จะถูกตรวจสอบ. |
| constant | const ConstantT\& | นิพจน์ที่เปรียบเทียบกับด้านซ้าย. |

### ค่าที่ส่งกลับ

true หากการตรวจสอบประเภทสำเร็จ, false หากไม่สำเร็จ.

## System::Is(const E\&, const A\&) ฟังก์ชัน

ฟังก์ชันการจับคู่ระดับบนสุด. ใช้แพทเทิร์นกับค่า.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```

### พารามิเตอร์แบบเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| A | ประเภทแพทเทิร์น (ต้องสืบทอดจาก Details::Pattern). |
| E | ประเภทของค่าที่จะจับคู่. |

### อาร์กูเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| e | const E\& | ค่าที่จะจับคู่กับ. |
| a | const A\& | แพทเทิร์นที่จะใช้. |

### ค่าที่ส่งกลับ

true หากแพทเทิร์นตรงกับค่า.

## ดูเพิ่มเติม

* Namespace [System](../)
* Library [Aspose.Slides](../../)