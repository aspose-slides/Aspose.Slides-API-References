---
title: ValueIterator
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตัววนซ้ำของพจนานุกรมที่ให้การเข้าถึงค่า.
type: docs
weight: 625
url: /th/system.collections.generic/valueiterator/
---
## ValueIterator คลาส


[Dictionary](../dictionary/) ตัววนซ้ำที่ให้การเข้าถึงค่า.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Dict | [Dictionary](../dictionary/) คลาส. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | ทำสำเนาตัววนซ้ำปัจจุบัน. |
| void [DecrementIterator](./decrementiterator/)() override | ย้ายตัววนซ้ำหนึ่งขั้นถอยหลัง. |
| void [IncrementIterator](./incrementiterator/)() override | ย้ายตัววนซ้ำหนึ่งขั้นไปข้างหน้า. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | ย้ายตัววนซ้ำตามจำนวนขั้นที่ระบุ. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | คอนสตรัคเตอร์. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | คอนสตรัคเตอร์. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | คอนสตรัคเตอร์การเคลื่อนย้าย. |
| virtual  [~ValueIterator](./~valueiterator/)() | ดีสตรัคเตอร์. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)