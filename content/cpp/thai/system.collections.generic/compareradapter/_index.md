---
title: ComparerAdapter
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: อะแด็ปเตอร์เพื่อใช้ IComparer ภายในสภาพแวดล้อม STL. ใช้ IComparer หากตั้งค่าไว้; หากไม่, จะใช้ตัวดำเนินการ < (หากมี) หรือคืนค่า false (หากไม่มี).
type: docs
weight: 638
url: /th/system.collections.generic/compareradapter/
---
## ComparerAdapter struct

อะแด็ปเตอร์เพื่อใช้ [IComparer](../icomparer/) ภายในสภาพแวดล้อม STL. ใช้ [IComparer](../icomparer/) หากตั้งค่าไว้; หากไม่, จะใช้ตัวดำเนินการ < (หากมี) หรือคืนค่า false (หากไม่มี).

```cpp
template<class T>class ComparerAdapter
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทที่กำลังเปรียบเทียบ. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | สร้างอะแด็ปเตอร์โดยไม่มีตัวเปรียบเทียบใด ๆ. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | สร้างอะแด็ปเตอร์. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) ฟังก์ชันสำหรับประเภทที่มีตัวดำเนินการ <. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) ฟังก์ชันสำหรับประเภทที่ไม่มีตัวดำเนินการ <. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | ตั้งค่าอ็อบเจกต์ตัวเปรียบเทียบ. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)