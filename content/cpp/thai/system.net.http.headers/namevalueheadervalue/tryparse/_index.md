---
title: TryParse()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: พยายามแปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส NameValueHeaderValue.
type: docs
weight: 105
url: /th/system.net.http.headers/namevalueheadervalue/tryparse/
---
## NameValueHeaderValue::TryParse(String, System::SharedPtr\<NameValueHeaderValue\>\&) เมธอด

พยายามแปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส [NameValueHeaderValue](../).

```cpp
static bool System::Net::Http::Headers::NameValueHeaderValue::TryParse(String input, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงสำหรับการแยกวิเคราะห์. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | อินสแตนซ์ที่วัตถุที่แยกวิเคราะห์แล้วจะถูกกำหนด. |

### ค่าที่ส่งกลับ

true เมื่อการแยกวิเคราะห์สำเร็จ, มิฉะนั้น false.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [NameValueHeaderValue](../)
* เนมสเปซ [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)