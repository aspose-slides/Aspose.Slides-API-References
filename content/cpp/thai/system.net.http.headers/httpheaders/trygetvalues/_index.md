---
title: TryGetValues()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: พยายามดึงค่าที่สอดคล้องกันตามชื่อที่ระบุ.
type: docs
weight: 66
url: /th/system.net.http.headers/httpheaders/trygetvalues/
---
## HttpHeaders::TryGetValues(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&) เมธอด

พยายามดึงค่าที่สอดคล้องกันจากชื่อที่ระบุ.

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryGetValues(String name, System::SharedPtr<Collections::Generic::IEnumerable<String>> &values)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อส่วนหัว. |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | อินสแตนซ์ที่ค่าที่สอดคล้องกันจะถูกกำหนด. |

### ค่าที่ส่งคืน

True เมื่อพบค่าหัวข้อตามชื่อที่ระบุ, หากไม่พบจะเป็น false.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [IEnumerable](../../../system.collections.generic/ienumerable/)
* คลาส [HttpHeaders](../)
* เนมสเปซ [System::Net::Http::Headers](../../)
* ไลบรารี [Aspose.Slides](../../../)