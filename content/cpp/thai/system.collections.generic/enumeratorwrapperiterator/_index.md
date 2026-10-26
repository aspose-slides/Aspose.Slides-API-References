---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: Iterator ที่ห่อหุ้ม enumerator ที่สร้างไว้ล่วงหน้าและเปลี่ยนทิศทางของการเรียกทั้งหมดไปยังมัน.
type: docs
weight: 196
url: /th/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator คลาส


Iterator ที่ห่อหุ้ม enumerator ที่สร้างไว้ล่วงหน้าและเปลี่ยนทิศทางของการเรียกทั้งหมดไปยังมัน

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```


### Template parameters

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Element | ประเภทของ Element |
## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | สร้างสำเนา iterator ปัจจุบัน |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | เลื่อน iterator ไปข้างหน้าหนึ่งขั้น ต้องอัปเดต m_is_end และ m_pointer |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | ตรวจสอบว่า iterator สองตัวชี้ไปยังรายการเดียวกันหรือไม่ |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | ตัวทำลาย |
## ดูเพิ่มเติม

* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)