---
title: ValueTuple
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คลาสที่เป็นตัวแทนของโครงสร้างข้อมูล ValueTuple.
type: docs
weight: 1444
url: /th/system/valuetuple/
---
## ValueTuple คลาส


คลาสที่เป็นตัวแทนของโครงสร้างข้อมูล [ValueTuple](./).

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | กำหนดว่าวัตถุปัจจุบันและวัตถุที่ระบุเป็นเหมือนกันหรือไม่ |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | รับอ้างอิงไปยังค่าของส่วนประกอบของวัตถุ [ValueTuple](./) |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | รับค่าของส่วนประกอบของวัตถุ [ValueTuple](./) |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | แยกวัตถุออกเป็น value tuple นี้ |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | คืนอ้างอิงไปยังวัตถุ [TypeInfo](../typeinfo/) ที่แสดงข้อมูลประเภทคลาส [ValueTuple](./) |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | สร้างวัตถุ tuple |
## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)