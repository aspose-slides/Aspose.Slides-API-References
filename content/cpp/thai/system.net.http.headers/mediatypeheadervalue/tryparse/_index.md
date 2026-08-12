---
title: TryParse()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: พยายามแปลงสตริงที่ส่งเข้ามาให้เป็นอินสแตนซ์ของคลาส MediaTypeHeaderValue
type: docs
weight: 131
url: /th/system.net.http.headers/mediatypeheadervalue/tryparse/
---
## MediaTypeHeaderValue::TryParse(String, System::SharedPtr\<MediaTypeHeaderValue\>\&) เมธอด

พยายามแปลงสตริงที่ส่งเข้ามาให้เป็นอินสแตนซ์ของคลาส [MediaTypeHeaderValue](../).

```cpp
static bool System::Net::Http::Headers::MediaTypeHeaderValue::TryParse(String input, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงที่จะทำการแยกวิเคราะห์. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | อินสแตนซ์ที่วัตถุที่แยกวิเคราะห์แล้วจะถูกกำหนดค่าให้. |

### ค่าที่ส่งกลับ

คืนค่า true หากการพาร์เซสำเร็จ มิฉะนั้นคืนค่า false.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [MediaTypeHeaderValue](../)
* เนมสเปซ [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)