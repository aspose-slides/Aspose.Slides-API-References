---
title: EqualityComparerAdapter
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "อะแดปเตอร์ที่ทำให้สามารถใช้ IEqualityComparer กับคอลเลกชันและอัลกอริธึมสไตล์ STL ได้ หากกำหนด IEqualityComparer จะใช้ค่านั้น หากไม่ได้กำหนดจะใช้ตัวดำเนินการ ==, Object::Equals หรือ T::Equals, ตามที่มีให้ใช้"
type: docs
weight: 664
url: /th/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter struct

Adapter making it possible using [IEqualityComparer](../iequalitycomparer/) with STL-styled collections and algorithms. Uses [IEqualityComparer](../iequalitycomparer/), if set. If not set, uses operator ==, [Object::Equals](../../system/object/equals/) or T::Equals, whichever is available.

```cpp
template<class T>class EqualityComparerAdapter
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดที่เปรียบเทียบ |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | สร้างแปลงโดยไม่ใช้ตัวเปรียบเทียบใด ๆ |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | สร้างแปลงด้วยตัวเปรียบเทียบที่กำหนด |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | เปรียบเทียบสองอ็อบเจกต์ |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | ตั้งค่าตัวเปรียบเทียบ |

## ดูเพิ่มเติม

* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)