---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "หากคอลเลกชันมีจุดข้อมูลที่ดัชนี index อยู่แล้ว จะคืนค่าส่วนนี้ หากคอลเลกชันไม่มีจุดข้อมูลที่ดัชนี index ==N (เมื่อจำนวนจุดข้อมูลในคอลเลกชันนี้น้อยกว่าหรือเท่ากับ N) จะเพิ่มจุดข้อมูลที่ขาดหายและคืนค่าจุดสุดท้าย (ซึ่งมีดัชนีที่ร้องขอ) ตัวอย่างเช่น ดัชนีของคอลเลกชันคือ {0, 1, 2} และดัชนีที่ร้องขอคือ 5 จากนั้นเมธอดจะเพิ่มจุดข้อมูลที่ขาดหาย: {0, 1, 2, 3, 4, 5} และคืนค่าจุดข้อมูลที่มีดัชนี 5."
type: docs
weight: 131
url: /th/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) เมธอด

ถ้าคอลเลกชันมีจุดข้อมูลที่มีดัชนี *index* อยู่แล้ว จะคืนค่าจุดข้อมูลนั้น ถ้าคอลเลกชันไม่มีจุดข้อมูลที่ดัชนี *index* ==N (เมื่อจำนวนจุดข้อมูลในคอลเลกชันนี้น้อยกว่าหรือเท่ากับ N) จะเพิ่มจุดข้อมูลที่ขาดหายและคืนค่าจุดสุดท้าย (ซึ่งมีดัชนีที่ร้องขอ) ตัวอย่างเช่น ดัชนีของคอลเลกชันคือ {0, 1, 2} และดัชนีที่ร้องขอคือ 5 จากนั้นเมธอดจะเพิ่มจุดข้อมูลที่ขาดหาย: {0, 1, 2, 3, 4, 5} และคืนค่าจุดข้อมูลที่มีดัชนี 5.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **uint32_t** | ดัชนี. |

### ค่าที่ส่งกลับ

คืนค่าจุดข้อมูลที่มีดัชนีที่ร้องขอ.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IChartDataPoint](../../ichartdatapoint/)
* คลาส [IChartDataPointCollection](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)