---
title: GetEntityTagLength()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงสตริงที่ส่งเข้ามาจากตำแหน่งที่ระบุเป็นอินสแตนซ์ของคลาส EntityTagHeaderValue.
type: docs
weight: 118
url: /th/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) เมธอด


แปลงสตริงที่ส่งเข้ามาจากตำแหน่งที่ระบุเป็นอินสแตนซ์ของคลาส [EntityTagHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงสำหรับการวิเคราะห์. |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการวิเคราะห์. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | อินสแตนซ์ที่วัตถุที่วิเคราะห์แล้วจะถูกกำหนด. |

### ค่าที่ส่งคืน

ความยาวของสตริงย่อยที่วิเคราะห์แล้ว, มิฉะนั้นเป็น 0.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [EntityTagHeaderValue](../)
* เนมสเปส [System::Net::Http::Headers](../../)
* ไลบรารี [Aspose.Slides](../../../)