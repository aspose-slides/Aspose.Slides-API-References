---
title: GetRangeLength()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: แปลงสตริงที่ส่งเข้ามาจากดัชนีที่ระบุเป็นอินสแตนซ์ของคลาส RangeHeaderValue.
type: docs
weight: 118
url: /th/system.net.http.headers/rangeheadervalue/getrangelength/
---
## RangeHeaderValue::GetRangeLength(String, int32_t, System::SharedPtr\<Object\>\&) เมธอด

แปลงสตริงที่ส่งเข้ามาจากดัชนีที่ระบุเป็นอินสแตนซ์ของคลาส [RangeHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::RangeHeaderValue::GetRangeLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงเพื่อแยกวิเคราะห์. |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการแยกวิเคราะห์. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | อินสแตนซ์ที่วัตถุที่แยกวิเคราะห์แล้วจะถูกกำหนด. |

### ค่าผลลัพธ์

คืนความยาวของส่วนย่อยที่แยกวิเคราะห์, หากไม่เป็นเช่นนั้นจะคืนค่า 0.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [Object](../../../system/object/)
* คลาส [RangeHeaderValue](../)
* เนมสเปซ [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)