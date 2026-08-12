---
title: GetViaLength()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงสตริงที่ส่งเข้ามาจากดัชนีที่ระบุเป็นอินสแตนซ์ของคลาส ViaHeaderValue.
type: docs
weight: 131
url: /th/system.net.http.headers/viaheadervalue/getvialength/
---
## ViaHeaderValue::GetViaLength(String, int32_t, System::SharedPtr\<Object\>\&) เมธอด

แปลงสตริงที่ส่งเข้ามาจากดัชนีที่ระบุเป็นอินสแตนซ์ของคลาส [ViaHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::ViaHeaderValue::GetViaLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงที่ต้องการแยกวิเคราะห์ |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการแยกวิเคราะห์ |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | อินสแตนซ์ที่วัตถุที่แยกวิเคราะห์จะถูกกำหนด |

### ค่าที่ส่งคืน

ส่งคืนความยาวของสตริงย่อยที่แยกวิเคราะห์ มิฉะนั้นคืนค่า 0.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [Object](../../../system/object/)
* คลาส [ViaHeaderValue](../)
* เนมสเปซ [System::Net::Http::Headers](../../)
* ไลบรารี [Aspose.Slides](../../../)