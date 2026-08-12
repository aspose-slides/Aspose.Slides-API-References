---
title: DictionaryIterator
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตัวดำเนินการพจนานุกรมที่ให้สัญกรณ์ KeyValuePair
type: docs
weight: 157
url: /th/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator คลาส


[Dictionary](../dictionary/) ตัวดำเนินการที่ให้ [KeyValuePair](../keyvaluepair/) สัญกรณ์.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Dict | [Dictionary](../dictionary/) คลาส. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | ทำสำเนาตัวดำเนินการปัจจุบัน. |
| void [DecrementIterator](./decrementiterator/)() override | เลื่อนตัวดำเนินการถอยหลังหนึ่งขั้น. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | คอนสตรัคเตอร์. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | คอนสตรัคเตอร์. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | คอนสตรัคเตอร์การย้าย. |
| void [IncrementIterator](./incrementiterator/)() override | เลื่อนตัวดำเนินการไปข้างหน้าหนึ่งขั้น. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | เลื่อนตัวดำเนินการตามจำนวนขั้นที่ระบุ. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | ดีสตรัคเตอร์. |

## ดูเพิ่มเติม

* เนมสเปส [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)