---
title: TestCompare
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: โครงสร้างบริการที่ให้ส่วนต่อประสานเพื่อเปรียบเทียบคอลเลกชัน.
type: docs
weight: 1912
url: /th/system/testcompare/
---
## TestCompare struct

โครงสร้างบริการที่ให้ส่วนต่อประสานเพื่อเปรียบเทียบคอลเลกชัน

```cpp
class TestCompare
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static **bool** [AbstractEqual](./abstractequal/)([SCG::ICollection](../../system.collections.generic/icollection/)\<T\> *const, [SCG::ICollection](../../system.collections.generic/icollection/)\<T\> *const) | เปรียบเทียบคอลเลกชันสองชุดที่มีประเภทไม่ทราบ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<U\>\>\&) | เปรียบเทียบอาร์เรย์ที่ไม่เป็นพอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | เปรียบเทียบอาร์เรย์ของพอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<U\>\>\&) | เปรียบเทียบลิสต์ที่ไม่เป็นพอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | เปรียบเทียบลิสต์ของพอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<T\>\>\&, const [System::ArrayPtr](../arrayptr/)\<U\>\&) | เปรียบเทียบลิสต์กับอาร์เรย์ในกรณีที่สมาชิกไม่เป็นพอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [System::ArrayPtr](../arrayptr/)\<T\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<U\>\>\&) | เปรียบเทียบลิสต์กับอาร์เรย์ในกรณีที่สมาชิกไม่เป็นพอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [System::ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | เปรียบเทียบลิสต์กับอาร์เรย์ในกรณีที่สมาชิกเป็นพอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::List](../../system.collections.generic/list/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [System::ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<U\>\>\&) | เปรียบเทียบลิสต์กับอาร์เรย์ในกรณีที่สมาชิกเป็นพอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, U\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, U\>\>\&) | เปรียบเทียบดิกชันนารีของประเภทที่แมปโดยไม่ใช้พอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&) | เปรียบเทียบดิกชันนารีของประเภทที่แมปโดยใช้พอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K1, U1\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Dictionary](../../system.collections.generic/dictionary/)\<K2, U2\>\>\&) | เปรียบเทียบดิกชันนารีของประเภทที่แตกต่างกัน |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<U\>\>\&) | เปรียบเทียบแฮชเซ็ตที่ไม่เป็นพอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::HashSet](../../system.collections.generic/hashset/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | เปรียบเทียบแฮชเซ็ตของพอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<T\>\&, const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<U\>\&) | เปรียบเทียบคิวที่ไม่เป็นพอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<[SharedPtr](../sharedptr/)\<T\>\>\&, const [SCG::QueuePtr](../../system.collections.generic/queueptr/)\<[SharedPtr](../sharedptr/)\<U\>\>\&) | เปรียบเทียบคิวของพอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<T\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<U\>\>\&) | เปรียบเทียบสแตกที่ไม่เป็นพอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<[SharedPtr](../sharedptr/)\<T\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::Stack](../../system.collections.generic/stack/)\<[SharedPtr](../sharedptr/)\<U\>\>\>\&) | เปรียบเทียบสแตกของพอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, U\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, U\>\>\&) | เปรียบเทียบดิกชันนารีที่เรียงลำดับของประเภทที่แมปโดยไม่ใช้พอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&) | เปรียบเทียบดิกชันนารีที่เรียงลำดับของประเภทที่แมปโดยใช้พอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedDictionary](../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\&) | เปรียบเทียบดิกชันนารีที่เรียงลำดับของประเภทที่แตกต่างกัน |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, U\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, U\>\>\&) | เปรียบเทียบลิสต์ที่เรียงลำดับของประเภทที่แมปโดยไม่ใช้พอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../sharedptr/)\<U\>\>\>\&) | เปรียบเทียบลิสต์ที่เรียงลำดับของประเภทที่แมปโดยใช้พอยน์เตอร์ |
| static **bool** [AreEqual](./areequal/)(const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K1, U1\>\>\&, const [SharedPtr](../sharedptr/)\<[SCG::SortedList](../../system.collections.generic/sortedlist/)\<K2, U2\>\>\&) | เปรียบเทียบลิสต์ที่เรียงลำดับของประเภทที่แตกต่างกัน |
| static **bool** [AreEqual](./areequal/)(const [System::Collections::Specialized::StringCollectionPtr](../../system.collections.specialized/stringcollectionptr/)\&, const [System::Collections::Specialized::StringCollectionPtr](../../system.collections.specialized/stringcollectionptr/)\&) | เปรียบเทียบคอลเลกชันสตริง |
| static **bool** [AreEqual](./areequal/)(const [System::SharedPtr](../sharedptr/)\<[SCG::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&, const [System::SharedPtr](../sharedptr/)\<[SCG::IEnumerable](../../system.collections.generic/ienumerable/)\<U\>\>\&) | เปรียบเทียบอินสแตนซ์ของ IEnumerable |
## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)