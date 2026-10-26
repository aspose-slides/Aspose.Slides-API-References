---
title: GetNameValueLength()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงสตริงที่ส่งเข้ามาจากดัชนีที่ระบุเป็นอินสแตนซ์ของคลาส NameValueHeaderValue.
type: docs
weight: 118
url: /th/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) เมธอด


แปลงสตริงที่ส่งเข้ามาจากดัชนีที่ระบุเป็นอินสแตนซ์ของคลาส [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงเพื่อทำการแยกวิเคราะห์. |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการแยกวิเคราะห์. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | อินสแตนซ์ที่วัตถุที่ทำการแยกจะแอสไกนเข้าไป. |

### ค่าที่ส่งคืน

ส่งคืนความยาวของสับสตริงที่ทำการแยก, มิฉะนั้น 0.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) เมธอด


แปลงสตริงที่ส่งเข้ามาจากดัชนีที่ระบุเป็นอินสแตนซ์ของคลาส [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงเพื่อทำการแยกวิเคราะห์. |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการแยกวิเคราะห์. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | ฟังก์ชันที่ใช้เพื่อสร้างอินสแตนซ์ใหม่ของ [NameValueHeaderValue](../) คลาส. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | อินสแตนซ์ที่วัตถุที่ทำการแยกจะแอสไกนเข้าไป. |

### ค่าที่ส่งคืน

ส่งคืนความยาวของสับสตริงที่ทำการแยก, มิฉะนั้น 0.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Class [String](../../../system/string/)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)