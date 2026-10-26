---
title: GetNameValueWithParametersLength()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงสตริงที่ส่งเข้ามาจากตำแหน่งที่ระบุเป็นอินสแตนซ์ของคลาส NameValueWithParametersHeaderValue.
type: docs
weight: 92
url: /th/system.net.http.headers/namevaluewithparametersheadervalue/getnamevaluewithparameterslength/
---
## NameValueWithParametersHeaderValue::GetNameValueWithParametersLength(String, int32_t, System::SharedPtr\<Object\>\&) เมธอด


แปลงสตริงที่ส่งเข้ามาจากตำแหน่งที่ระบุเป็นอินสแตนซ์ของคลาส [NameValueWithParametersHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueWithParametersHeaderValue::GetNameValueWithParametersLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงสำหรับแยกวิเคราะห์. |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการแยกวิเคราะห์. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | อินสแตนซ์ที่วัตถุที่แยกวิเคราะห์จะถูกกำหนด. |

### ค่าที่ส่งกลับ

ส่งคืนความยาวของส่วนย่อยสตริงที่แยกวิเคราะห์, มิฉะนั้น 0.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [Object](../../../system/object/)
* คลาส [NameValueWithParametersHeaderValue](../)
* เนมสเปซ [System::Net::Http::Headers](../../)
* ไลบรารี [Aspose.Slides](../../../)