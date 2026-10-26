---
title: GetRangeItemLength()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงสตริงที่ส่งเข้ามาจากตำแหน่งที่ระบุเป็นอินสแตนซ์ของคลาส RangeItemHeaderValue.
type: docs
weight: 92
url: /th/system.net.http.headers/rangeitemheadervalue/getrangeitemlength/
---
## RangeItemHeaderValue::GetRangeItemLength(String, int32_t, System::SharedPtr\<RangeItemHeaderValue\>\&) เมธอด

แปลงสตริงที่ส่งเข้ามาจากตำแหน่งที่ระบุเป็นอินสแตนซ์ของคลาส [RangeItemHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength(String input, int32_t startIndex, System::SharedPtr<RangeItemHeaderValue> &parsedValue)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงสำหรับพาร์ส. |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการพาร์ส. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\& | อินสแตนซ์ที่วัตถุที่พาร์สแล้วจะถูกกำหนด. |

### ค่าที่ส่งกลับ

ส่งคืนความยาวของสับสตริงที่พาร์ส, มิฉะนั้นจะคืนค่า 0.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [RangeItemHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)