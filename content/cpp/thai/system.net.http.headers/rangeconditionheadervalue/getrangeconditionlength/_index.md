---
title: GetRangeConditionLength()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงสตริงที่ส่งเข้ามาจากตำแหน่งที่ระบุให้เป็นออบเจ็กต์ของคลาส RangeConditionHeaderValue.
type: docs
weight: 105
url: /th/system.net.http.headers/rangeconditionheadervalue/getrangeconditionlength/
---
## RangeConditionHeaderValue::GetRangeConditionLength(String, int32_t, System::SharedPtr\<Object\>\&) เมธอด

แปลงสตริงที่ส่งเข้ามาจากตำแหน่งที่ระบุให้เป็นออบเจ็กต์ของคลาส [RangeConditionHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::RangeConditionHeaderValue::GetRangeConditionLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงที่ต้องการแยกวิเคราะห์ |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการแยกวิเคราะห์ |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | อินสแตนซ์ที่วัตถุที่แยกวิเคราะห์แล้วจะถูกกำหนดค่าให้ |

### ค่าที่ส่งคืน

ส่งคืนความยาวของสตริงย่อยที่แยกวิเคราะห์แล้ว, หากไม่เป็นเช่นนั้นจะเป็น 0

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [Object](../../../system/object/)
* คลาส [RangeConditionHeaderValue](../)
* เนมสเปซ [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)