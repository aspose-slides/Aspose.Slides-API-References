---
title: GetRangeItemListLength()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงสตริงที่ส่งเข้ามาจากตำแหน่งที่ระบุเป็นคอลเลกชันของอินสแตนซ์แบบ RangeItemHeaderValue-class
type: docs
weight: 79
url: /th/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) method


แปลงสตริงที่ส่งเข้ามาจากตำแหน่งที่ระบุเป็นคอลเลกชันของอินสแตนซ์แบบ RangeItemHeaderValue-class

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | สตริงที่จะทำการแยกวิเคราะห์ |
| startIndex | **int32_t** | ตำแหน่งเริ่มต้นสำหรับการแยกวิเคราะห์ |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | อินสแตนซ์ที่คอลเลกชันที่แยกวิเคราะห์แล้วจะถูกกำหนด |

### Return Value

ความยาวของส่วนย่อยสตริงที่แยกวิเคราะห์, หากไม่มีจะเป็น 0

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [ICollection](../../../system.collections.generic/icollection/)
* คลาส [RangeItemHeaderValue](../)
* เนมสเปซ [System::Net::Http::Headers](../../)
* ไลบรารี [Aspose.Slides](../../../)