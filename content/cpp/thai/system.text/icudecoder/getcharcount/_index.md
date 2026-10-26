---
title: GetCharCount()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับจำนวนอักขระที่จำเป็นสำหรับการถอดรหัสบัฟเฟอร์
type: docs
weight: 40
url: /th/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) เมธอด

รับจำนวนอักขระที่ต้องการสำหรับการถอดรหัสบัฟเฟอร์

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ไบต์สำหรับการถอดรหัส |
| index | int | [Buffer](../../../system/buffer/) ออฟเซต |
| count | int | จำนวนไบต์ที่ต้องถอดรหัส |

### ค่าที่ส่งกลับ

จำนวนอักขระที่จำเป็นสำหรับการถอดรหัสบัฟเฟอร์

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) เมธอด

รับจำนวนอักขระที่ต้องการสำหรับการถอดรหัสบัฟเฟอร์

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ไบต์สำหรับการถอดรหัส |
| index | int | [Buffer](../../../system/buffer/) ออฟเซต |
| count | int | จำนวนไบต์ที่ต้องถอดรหัส |
| flush | **bool** | หากเป็น true จะทำความสะอาดสถานะของตัวถอดรหัสภายในหลังการคำนวณ |

### ค่าที่ส่งกลับ

จำนวนอักขระที่จำเป็นสำหรับการถอดรหัสบัฟเฟอร์

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) เมธอด

รับจำนวนอักขระที่ต้องการสำหรับการถอดรหัสบัฟเฟอร์

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | ไบต์สำหรับการถอดรหัส |
| count | int | จำนวนไบต์ที่ต้องถอดรหัส |
| flush | **bool** | หากเป็น true จะทำความสะอาดสถานะของตัวถอดรหัสภายในหลังการคำนวณ |

### ค่าที่ส่งกลับ

จำนวนอักขระที่จำเป็นสำหรับการถอดรหัสบัฟเฟอร์

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ICUDecoder](../)
* เนมสเปซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)