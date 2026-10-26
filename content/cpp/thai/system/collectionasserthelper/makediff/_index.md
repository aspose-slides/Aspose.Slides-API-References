---
title: MakeDiff()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: คำนวณ 'diff' ระหว่างสองคอลเลกชัน สำหรับแต่ละองค์ประกอบของแต่ละคอลเลกชันเป็นคีย์ ค่าที่ได้จะเป็นบวกหากองค์ประกอบปรากฏบ่อยกว่าในคอลเลกชัน \"expected\" ค่าลบหากปรากฏบ่อยกว่าในคอลเลกชัน \"actual\" และศูนย์หากปรากฏจำนวนเท่ากันในแต่ละคอลเลกชัน.
type: docs
weight: 1
url: /th/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) เมธอด

คำนวณ 'diff' ระหว่างสองคอลเลกชัน สำหรับแต่ละองค์ประกอบของแต่ละคอลเลกชันเป็นคีย์ ค่าที่ได้จะเป็นบวกหากองค์ประกอบปรากฏบ่อยกว่าในคอลเลกชัน \"expected\" เป็นลบหากปรากฏบ่อยกว่าในคอลเลกชัน \"actual\" และเป็นศูนย์หากปรากฏเท่าเทียมกันในแต่ละคอลเลกชัน.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทขององค์ประกอบคอลเลกชันที่คาดหวัง. |
| T2 | ประเภทขององค์ประกอบคอลเลกชันจริง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | คอลเลกชันที่คาดหวัง. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | คอลเลกชันจริง. |

### ค่าที่ส่งกลับ

แผนที่ของผลการเปรียบเทียบแต่ละค่า ตามกฎข้างต้น.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [Dictionary](../../../system.collections.generic/dictionary/)
* คลาส [IEnumerable](../../../system.collections.generic/ienumerable/)
* โครงสร้าง [CollectionAssertHelper](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)