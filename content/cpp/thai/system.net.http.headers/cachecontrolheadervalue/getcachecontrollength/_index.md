---
title: GetCacheControlLength()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงสตริงที่ส่งเข้ามาตั้งแต่ดัชนีที่ระบุเป็นอินสแตนซ์ของคลาส CacheControlHeaderValue.
type: docs
weight: 456
url: /th/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) เมธอด

แปลงสตริงที่ส่งเข้ามาตั้งแต่ตำแหน่งที่ระบุเป็นอินสแตนซ์ของคลาส [CacheControlHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงสำหรับแยกวิเคราะห์. |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการแยกวิเคราะห์. |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | ค่าที่ต้องเพิ่มเข้าไปในอ็อบเจ็กต์ที่แยกวิเคราะห์แล้ว. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | อินสแตนซ์ที่อ็อบเจ็กต์ที่แยกวิเคราะห์แล้วจะถูกกำหนดค่า. |

### ค่าที่คืน

ความยาวของสับสตริงที่แยกวิเคราะห์, หรือ 0 หากไม่มี.

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [CacheControlHeaderValue](../)
* เนมสเปซ [System::Net::Http::Headers](../../)
* ไลบรารี [Aspose.Slides](../../../)