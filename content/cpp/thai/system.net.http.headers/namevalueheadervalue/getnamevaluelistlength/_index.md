---
title: GetNameValueListLength()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงสตริงที่ส่งเข้ามาตั้งแต่ตำแหน่งที่ระบุเป็นคอลเลกชันของอินสแตนซ์ในคลาส NameValueHeaderValue และคืนความยาวของสตริงย่อยที่ถูกแยกวิเคราะห์.
type: docs
weight: 131
url: /th/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) method

แปลงสตริงที่ส่งเข้ามาตั้งแต่ตำแหน่งที่ระบุเป็นคอลเลกชันของอินสแตนซ์ในคลาส NameValueHeaderValue และคืนความยาวของสตริงย่อยที่ถูกแยกวิเคราะห์

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงเพื่อวิเคราะห์. |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการวิเคราะห์. |
| delimiter | char16_t | สตริงที่ใช้เป็นตัวแบ่งรายการในสตริงที่ระบุ. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | พารามิเตอร์ผลลัพธ์ที่คอลเลกชันที่แยกวิเคราะห์จะถูกกำหนด. |

### ค่าที่ส่งคืน

ความยาวของสตริงย่อยที่ถูกแยกวิเคราะห์.

## ดูเพิ่ม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ObjectCollection](../../objectcollection/)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)