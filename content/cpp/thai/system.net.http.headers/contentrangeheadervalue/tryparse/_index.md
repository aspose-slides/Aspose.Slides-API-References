---
title: TryParse()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: พยายามแปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส ContentRangeHeaderValue.
type: docs
weight: 157
url: /th/system.net.http.headers/contentrangeheadervalue/tryparse/
---
## ContentRangeHeaderValue::TryParse(String, System::SharedPtr\<ContentRangeHeaderValue\>\&) เมธอด

พยายามแปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส [ContentRangeHeaderValue](../).

```cpp
static bool System::Net::Http::Headers::ContentRangeHeaderValue::TryParse(String input, System::SharedPtr<ContentRangeHeaderValue> &parsedValue)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงเพื่อทำการแยกวิเคราะห์ |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ContentRangeHeaderValue](../)\>\& | อินสแตนซ์ที่วัตถุที่แยกวิเคราะห์แล้วจะถูกกำหนดให้ |

### ค่าที่คืน

True เมื่อการแยกวิเคราะห์ทำสำเร็จ, มิฉะนั้น false.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ContentRangeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)