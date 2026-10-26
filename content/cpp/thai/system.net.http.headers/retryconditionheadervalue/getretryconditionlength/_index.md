---
title: GetRetryConditionLength()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงสตริงที่ส่งเข้ามาจากดัชนีที่ระบุเป็นอินสแตนซ์ของคลาส RetryConditionHeaderValue
type: docs
weight: 105
url: /th/system.net.http.headers/retryconditionheadervalue/getretryconditionlength/
---
## RetryConditionHeaderValue::GetRetryConditionLength(String, int32_t, System::SharedPtr\<Object\>\&) เมธอด

แปลงสตริงที่ส่งเข้ามาจากดัชนีที่ระบุเป็นอินสแตนซ์ของคลาส [RetryConditionHeaderValue](../)

```cpp
static int32_t System::Net::Http::Headers::RetryConditionHeaderValue::GetRetryConditionLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงที่จะทำการแยกวิเคราะห์ |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการแยกวิเคราะห์ |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | อินสแตนซ์ที่วัตถุที่แยกวิเคราะห์แล้วจะถูกกำหนด |

### ค่าที่คืน

ส่งคืนความยาวของส่วนย่อยสตริงที่แยกวิเคราะห์ หากไม่เช่นนั้นจะคืนค่า 0.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [Object](../../../system/object/)
* คลาส [RetryConditionHeaderValue](../)
* เนมสเปซ [System::Net::Http::Headers](../../)
* ไลบรารี [Aspose.Slides](../../../)