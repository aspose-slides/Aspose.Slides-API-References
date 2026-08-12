---
title: TryParse()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: พยายามแปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส AuthenticationHeaderValue
type: docs
weight: 105
url: /th/system.net.http.headers/authenticationheadervalue/tryparse/
---
## AuthenticationHeaderValue::TryParse(String, System::SharedPtr\<AuthenticationHeaderValue\>\&) เมธอด

พยายามแปลงสตริงที่ได้รับเป็นอินสแตนซ์ของคลาส [AuthenticationHeaderValue](../).

```cpp
static bool System::Net::Http::Headers::AuthenticationHeaderValue::TryParse(String input, System::SharedPtr<AuthenticationHeaderValue> &parsedValue)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงเพื่อแยกวิเคราะห์ |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[AuthenticationHeaderValue](../)\>\& | อินสแตนซ์ที่วัตถุที่แยกวิเคราะห์จะถูกกำหนดค่า |

### ค่าที่คืน

true เมื่อการแยกวิเคราะห์ทำสำเร็จ, มิฉะนั้น false.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [AuthenticationHeaderValue](../)
* เนมสเปซ [System::Net::Http::Headers](../../)
* ไลบรารี [Aspose.Slides](../../../)