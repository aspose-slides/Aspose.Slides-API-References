---
title: CollectionAssertHelper
second_title: Aspose.Slides สำหรับ C++ API เอกสารอ้างอิง
description: Heler API สำหรับการดำเนินการที่เกี่ยวกับคอลเลกชัน.
type: docs
weight: 1548
url: /th/system/collectionasserthelper/
---
## CollectionAssertHelper struct

Heler API for collection-related operations.

```cpp
class CollectionAssertHelper
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | ตรวจสอบว่าอิลิเมนต์ทั้งหมดของคอลเลกชันเป็นไปตามเงื่อนไข |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | ตรวจสอบว่าอิลิเมนต์ใดๆ ของคอลเลกชันเป็นไปตามเงื่อนไข |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | ทำการซีเรียลไลซ์สองคอลเลกชันเพื่อเป็นตัวแทนข้อความ |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | แปลงคอลเลกชันเป็นสตริงโดยเชื่อมต่อการแสดงผลสตริงของอิลิเมนต์ |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | คำนวณ 'diff' ระหว่างสองคอลเลกชัน สำหรับแต่ละอิลิเมนต์ของแต่ละคอลเลกชันที่เป็นคีย์ ค่าที่ได้จะเป็นบวกหากอิลิเมนต์ปรากฏบ่อยกว่ากลุ่ม \"expected\" มากกว่า, เป็นลบหากอิลิเมนต์ปรากฏบ่อยกว่ากลุ่ม \"actual\" มากกว่า, และเป็นศูนย์หากอิลิเมนต์ปรากฏเท่ากันในแต่ละคอลเลกชัน |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | จัดรูปแบบสตริงเพื่อใช้เป็นข้อความ |
## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)