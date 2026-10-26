---
title: TestTools
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ให้ชุดของเมธอดที่มีประโยชน์ที่ตรวจสอบคุณสมบัติพื้นฐานบางอย่างของประเภทและฟังก์ชันที่แตกต่างกัน
type: docs
weight: 1925
url: /th/system/testtools/
---
## TestTools struct

ให้ชุดของเมธอดที่มีประโยชน์ที่ตรวจสอบคุณสมบัติพื้นฐานบางอย่างของประเภทและฟังก์ชันที่แตกต่างกัน

```cpp
class TestTools
```

## Methods

| Method | Description |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | ตรวจสอบว่าฟังก์ชันขว้างข้อยกเว้นประเภทใดก็ได้หรือไม่ |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | ตรวจสอบว่าสตริงว่างหรือไม่ |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | ตรวจสอบว่าคอลเลกชันว่างหรือไม่ |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | ตรวจสอบว่าค่าเฉพาะเป็นค่า null หรือไม่ [Version](../version/) สำหรับชนิดเชิงเลขและ enum |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | ตรวจสอบว่าค่าเฉพาะเป็นค่า null หรือไม่ [Version](../version/) สำหรับชนิดค่าไม่เชิงเลขและไม่เป็น enum |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | ตรวจสอบว่าค่าเฉพาะเป็นค่า null หรือไม่ [Version](../version/) สำหรับชนิดค่าไม่เชิงเลข |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | ตรวจสอบว่าค่าเฉพาะเป็นค่า null หรือไม่ [Version](../version/) สำหรับคู่คีย์-ค่า |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | ตรวจสอบว่าสตริงเป็นค่า null หรือไม่ |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | ตรวจสอบว่าคอลเลกชันเป็นค่า null หรือว่างหรือไม่ |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | ตรวจสอบว่าสตริงเป็นค่า null หรือว่างหรือไม่ |
## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)