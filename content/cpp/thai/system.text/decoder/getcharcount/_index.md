---
title: GetCharCount()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับจำนวนอักขระที่ต้องการเพื่อถอดรหัสบัฟเฟอร์
type: docs
weight: 40
url: /th/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) เมธอด

รับจำนวนอักขระที่ต้องการเพื่อถอดรหัสบัฟเฟอร์

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ไบต์สำหรับถอดรหัส |
| index | int | [Buffer](../../../system/buffer/) ออฟเซต |
| count | int | จำนวนไบต์สำหรับถอดรหัส |

### ค่าที่ส่งคืน

จำนวนอักขระที่จำเป็นในการถอดรหัสบัฟเฟอร์

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) เมธอด

รับจำนวนอักขระที่ต้องการเพื่อถอดรหัสบัฟเฟอร์

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ไบต์สำหรับถอดรหัส |
| index | int | [Buffer](../../../system/buffer/) ออฟเซต |
| count | int | จำนวนไบต์สำหรับถอดรหัส |
| flush | **bool** | หากเป็น true จะทำความสะอาดสถานะ decoder ภายในหลังการคำนวน |

### ค่าที่ส่งคืน

จำนวนอักขระที่จำเป็นในการถอดรหัสบัฟเฟอร์

## Decoder::GetCharCount(const uint8_t *, int, bool) เมธอด

รับจำนวนอักขระที่ต้องการเพื่อถอดรหัสบัฟเฟอร์

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | const **uint8_t** * | ไบต์สำหรับถอดรหัส |
| count | int | จำนวนไบต์สำหรับถอดรหัส |
| flush | **bool** | หากเป็น true จะทำความสะอาดสถานะ decoder ภายในหลังการคำนวน |

### ค่าที่ส่งคืน

จำนวนอักขระที่จำเป็นในการถอดรหัสบัฟเฟอร์

## ดูเพิ่มเติม

* typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [Decoder](../)
* เนมส페ซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)