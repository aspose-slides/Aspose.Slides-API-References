---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "หากคอลเลกชันมีจุดข้อมูลที่ดัชนี index อยู่แล้ว จะคืนจุดข้อมูลนั้น หากคอลเลกชันไม่มีจุดข้อมูลที่ดัชนี index ==N (เมื่อจำนวนจุดข้อมูลในคอลเลกชันนี้น้อยกว่าหรือเท่ากับ N) จะเพิ่มจุดข้อมูลที่ขาดและคืนค่าจุดข้อมูลสุดท้าย (ซึ่งมีดัชนีที่ร้องขอ) ตัวอย่างเช่น ดัชนีของคอลเลกชันคือ {0, 1, 2} และดัชนีที่ร้องขอคือ 5 แล้วเมธอดจะเพิ่มจุดข้อมูลที่ขาด: {0, 1, 2, 3, 4, 5} และคืนจุดข้อมูลที่ดัชนี 5."
type: docs
weight: 170
url: /th/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) เมธอด

หากคอลเลกชันมีจุดข้อมูลที่ดัชนี *index* อยู่แล้วจะคืนจุดข้อมูลนี้. หากคอลเลกชันไม่มีจุดข้อมูลที่ดัชนี *index* ==N (เมื่อจำนวนจุดข้อมูลในคอลเลกชันนี้น้อยกว่าหรือเท่ากับ N) จะเพิ่มจุดข้อมูลที่ขาดไปและคืนค่าจุดข้อมูลสุดท้าย (ซึ่งมีดัชนีที่ร้องขอ). เช่น ตัวอย่าง คอลเลกชันมีดัชนีเป็น {0, 1, 2} และดัชนีที่ร้องขอคือ 5 จากนั้นเมธอดจะเพิ่มจุดข้อมูลที่ขาดไป: {0, 1, 2, 3, 4, 5} และคืนจุดข้อมูลที่ดัชนี 5.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **uint32_t** | ดัชนี. |

### ค่าที่คืน

คืนค่าจุดข้อมูลที่ดัชนีที่ร้องขอ.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [ChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)