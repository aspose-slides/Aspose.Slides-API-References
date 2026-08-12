---
title: GetStringWithQualityLength()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงสตริงที่ส่งเข้ามาจากตำแหน่งที่ระบุเป็นอ็อบเจกต์ของคลาส StringWithQualityHeaderValue
type: docs
weight: 105
url: /th/system.net.http.headers/stringwithqualityheadervalue/getstringwithqualitylength/
---
## StringWithQualityHeaderValue::GetStringWithQualityLength(String, int32_t, System::SharedPtr\<Object\>\&) เมธอด

แปลงสตริงที่ส่งเข้ามาจากตำแหน่งที่ระบุเป็นอ็อบเจ็กต์ของคลาส [StringWithQualityHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::StringWithQualityHeaderValue::GetStringWithQualityLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงที่จะแยกวิเคราะห์ |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการแยกวิเคราะห์ |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | อินสแตนซ์ที่วัตถุที่แยกวิเคราะห์จะถูกกำหนด |

### ค่าที่ส่งคืน

ส่งคืนความยาวของส่วนย่อยที่ถูกแยกวิเคราะห์, มิฉะนั้นคืนค่า 0.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [StringWithQualityHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)