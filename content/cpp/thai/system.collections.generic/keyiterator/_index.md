---
title: KeyIterator
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: อิเทรเตอร์ของดิกชันนารีที่ให้การเข้าถึงคีย์.
type: docs
weight: 365
url: /th/system.collections.generic/keyiterator/
---
## KeyIterator คลาส

[Dictionary](../dictionary/) ตัวอิเทรเตอร์ที่ให้การเข้าถึงคีย์.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Dict | [Dictionary](../dictionary/) คลาส. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | ทำสำเนาตัวอิเทรเตอร์ปัจจุบัน. |
| void [DecrementIterator](./decrementiterator/)() override | ย้ายตัวอิเทรเตอร์ถอยหลังหนึ่งขั้น. |
| void [IncrementIterator](./incrementiterator/)() override | ย้ายตัวอิเทรเตอร์ไปข้างหน้าหนึ่งขั้น. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator&&, typename Dict::map_t::const_iterator&&) | คอนสตรัคเตอร์. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator&, const typename Dict::map_t::const_iterator&) | คอนสตรัคเตอร์. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)&&) | คอนสตรัคเตอร์การย้าย. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | ย้ายตัวอิเทรเตอร์ตามจำนวนขั้นที่ระบุ. |
| virtual  [~KeyIterator](./~keyiterator/)() | ตัวทำลาย. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)