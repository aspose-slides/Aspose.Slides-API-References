---
title: GetMediaTypeLength()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงสตริงที่ส่งเข้ามาจากตำแหน่งที่ระบุให้เป็นอินสแตนซ์ของคลาส MediaTypeHeaderValue.
type: docs
weight: 144
url: /th/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) เมธอด


แปลงสตริงที่ส่งเข้ามาจากตำแหน่งที่กำหนดเป็นอินสแตนซ์ของคลาส [MediaTypeHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงเพื่อทำการแปลง. |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการแปลง. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | เดลีกเกตที่ใช้สร้างอินสแตนซ์ของคลาส [MediaTypeHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | อินสแตนซ์ที่วัตถุที่แปลงแล้วจะถูกกำหนด. |

### ค่าที่ส่งคืน

คืนความยาวของส่วนย่อยที่แปลงแล้ว, มิฉะนั้นจะคืนค่า 0.

## ดูเพิ่มเติม

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [MediaTypeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)