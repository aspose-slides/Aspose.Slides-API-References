---
title: GetByteCount()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับจำนวนไบต์ที่ต้องการเพื่อเข้ารหัสบัฟเฟอร์.
type: docs
weight: 40
url: /th/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) method

รับจำนวนไบต์ที่ต้องการเพื่อเข้ารหัสบัฟเฟอร์

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | อักขระสำหรับเข้ารหัส |
| index | int | [Buffer](../../../system/buffer/) ออฟเซ็ต |
| count | int | จำนวนอักขระสำหรับเข้ารหัส |
| flush | **bool** | ถ้าเป็นจริง จะทำความสะอาดสถานะของตัวเข้ารหัสภายในหลังจากการคำนวณ |

### Return Value

จำนวนไบต์ที่ต้องการเพื่อเข้ารหัสบัฟเฟอร์

## ICUEncoder::GetByteCount(const char_t *, int, bool) method

รับจำนวนไบต์ที่ต้องการเพื่อเข้ารหัสบัฟเฟอร์

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | const char_t * | อักขระสำหรับเข้ารหัส |
| count | int | จำนวนอักขระสำหรับเข้ารหัส |
| flush | **bool** | ถ้าเป็นจริง จะทำความสะอาดสถานะของตัวเข้ารหัสภายในหลังจากการคำนวณ |

### Return Value

จำนวนไบต์ที่ต้องการเพื่อเข้ารหัสบัฟเฟอร์

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)