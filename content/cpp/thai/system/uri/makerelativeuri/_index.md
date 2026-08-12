---
title: MakeRelativeUri()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: กำหนดความแตกต่างระหว่าง URI ที่เป็นตัวแทนของอ็อบเจ็กต์ Uri ปัจจุบันและอ็อบเจ็กต์ที่ระบุ
type: docs
weight: 352
url: /th/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) เมธอด

กำหนดความแตกต่างระหว่าง URIs ที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ [Uri](../) ที่ระบุ

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | ค่าที่เปรียบเทียบ |

### ค่าที่ส่งคืน

หากชื่อโฮสต์และสคีมาของ URIs ที่เป็นตัวแทนของอ็อบเจ็กต์ปัจจุบันและ **toUri** เหมือนกันเมธอดนี้จะคืนค่า [Uri](../) ที่สัมพันธ์กันซึ่งเมื่อต่อกับอินสแตนซ์ URI ปัจจุบันแล้วจะให้ผลลัพธ์เป็น **toUri** หากชื่อโฮสต์หรือสคีมาต่างกันเมธอดนี้จะคืนค่าอ็อบเจ็กต์ [Uri](../) ที่เป็นตัวแทนของพารามิเตอร์ **uri**

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [Uri](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)