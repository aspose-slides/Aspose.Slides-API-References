---
title: GetByteCount()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับจำนวนไบต์ที่จำเป็นในการเข้ารหัสบัฟเฟอร์.
type: docs
weight: 40
url: /th/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) เมธอด


รับจำนวนไบต์ที่จำเป็นในการเข้ารหัสบัฟเฟอร์

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | อักขระสำหรับเข้ารหัส |
| index | int | [Buffer](../../../system/buffer/) ออฟเซ็ต |
| count | int | จำนวนอักขระที่ต้องเข้ารหัส |
| flush | **bool** | หากเป็น true, จะทำความสะอาดสถานะของตัวเข้ารหัสภายในหลังจากการคำนวณ |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่ต้องการสำหรับการเข้ารหัสบัฟเฟอร์

## Encoder::GetByteCount(const char_t *, int, bool) เมธอด


รับจำนวนไบต์ที่จำเป็นในการเข้ารหัสบัฟเฟอร์

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | อักขระสำหรับเข้ารหัส |
| count | int | จำนวนอักขระที่ต้องเข้ารหัส |
| flush | **bool** | หากเป็น true, จะทำความสะอาดสถานะของตัวเข้ารหัสภายในหลังจากการคำนวณ |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่ต้องการสำหรับการเข้ารหัสบัฟเฟอร์

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)