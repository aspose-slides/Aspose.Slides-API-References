---
title: GetAuthenticationLength()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แยกวิเคราะห์สตริงที่ระบุและคืนค่าตำแหน่งสุดท้ายของการแสดงผลสตริง
type: docs
weight: 118
url: /th/system.net.http.headers/authenticationheadervalue/getauthenticationlength/
---
## AuthenticationHeaderValue::GetAuthenticationLength(String, int32_t, System::SharedPtr\<Object\>\&) เมธอด

แยกวิเคราะห์สตริงที่ระบุและคืนค่าตำแหน่งสุดท้ายของการแสดงผลสตริง

```cpp
static int32_t System::Net::Http::Headers::AuthenticationHeaderValue::GetAuthenticationLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงที่ต้องถูกแยกวิเคราะห์ |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการแยกวิเคราะห์ |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | พารามิเตอร์ผลลัพธ์ที่ค่าที่แยกวิเคราะห์จะถูกกำหนด |

### ค่าที่คืน

ความยาวของส่วนย่อยที่แยกวิเคราะห์, หากไม่เป็นเช่นนั้นคืนค่า 0

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [Object](../../../system/object/)
* คลาส [AuthenticationHeaderValue](../)
* เนมสเปซ [System::Net::Http::Headers](../../)
* ไลบรารี [Aspose.Slides](../../../)