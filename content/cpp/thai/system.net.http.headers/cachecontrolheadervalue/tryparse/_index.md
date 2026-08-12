---
title: TryParse()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: พยายามแปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส CacheControlHeaderValue
type: docs
weight: 443
url: /th/system.net.http.headers/cachecontrolheadervalue/tryparse/
---
## CacheControlHeaderValue::TryParse(String, System::SharedPtr\<CacheControlHeaderValue\>\&) เมธอด

พยายามแปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส [CacheControlHeaderValue](../).

```cpp
static bool System::Net::Http::Headers::CacheControlHeaderValue::TryParse(String input, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงที่ต้องการแยกวิเคราะห์ |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | อินสแตนซ์ที่วัตถุที่ทำการแยกวิเคราะห์จะถูกกำหนด |

### Return Value

เป็น true เมื่อการแยกวิเคราะห์สำเร็จ, มิฉะนั้นเป็น false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [CacheControlHeaderValue](../)
* เนมสเปซ [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)