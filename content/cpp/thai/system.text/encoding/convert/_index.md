---
title: Convert()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลงไบต์ระหว่างการเข้ารหัสสองแบบ.
type: docs
weight: 378
url: /th/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr&, const EncodingPtr&, const ArrayPtr\<uint8_t\>) เมธอด

แปลงไบต์ระหว่างการเข้ารหัสสองแบบ.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)& | การเข้ารหัสต้นทาง. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)& | การเข้ารหัสปลายทาง. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>& | ไบต์ที่ต้องการแปลง. |

### ค่าที่ส่งคืน

ไบต์ที่แปลงแล้ว.

## Encoding::Convert(const EncodingPtr&, const EncodingPtr&, const ArrayPtr\<uint8_t\>, int, int) เมธอด

แปลงไบต์ระหว่างการเข้ารหัสสองแบบ.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)& | การเข้ารหัสต้นทาง. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)& | การเข้ารหัสปลายทาง. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>& | ไบต์ที่ต้องการแปลง. |
| index | int | จุดเริ่มต้นของส่วน. |
| count | int | ขนาดของส่วน. |

### ค่าที่ส่งคืน

ไบต์ที่แปลงแล้ว.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)