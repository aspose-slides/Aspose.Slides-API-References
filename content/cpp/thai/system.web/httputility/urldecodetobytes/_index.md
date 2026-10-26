---
title: UrlDecodeToBytes()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ถอดรหัสส่วนของ URI จากอาเรย์ของไบต์.
type: docs
weight: 14
url: /th/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) เมธอด

ถอดรหัสส่วนของ URI จากอาเรย์ของไบต์.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | ส่วนของ URI ที่เข้ารหัส |
 
### ค่าที่ส่งกลับ

ส่วนของ URI ที่ถอดรหัสแล้ว.

## HttpUtility::UrlDecodeToBytes(const String\&) เมธอด

ถอดรหัสส่วนของ URI จากสตริงไบต์.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | ส่วนของ URI ที่เข้ารหัส |

### ค่าที่ส่งกลับ

ส่วนของ URI ที่ถอดรหัสแล้ว.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) เมธอด

ถอดรหัสส่วนของ URI จากสตริง.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | ส่วนของ URI ที่เข้ารหัส |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | การเข้ารหัสที่ใช้ |

### ค่าที่ส่งกลับ

ส่วนของ URI ที่ถอดรหัสแล้ว.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด

ถอดรหัสส่วนของ URI จากอาเรย์ของไบต์.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | ส่วนของ URI ที่เข้ารหัส |
| offset | **int32_t** | ออฟเซ็ตในอาเรย์ไบต์ที่กำหนด |
| count | **int32_t** | จำนวนไบต์ที่จะอ่าน |

### ค่าที่ส่งกลับ

ส่วนของ URI ที่ถอดรหัสแล้ว.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [HttpUtility](../)
* คลาส [String](../../../system/string/)
* คลาส [Encoding](../../../system.text/encoding/)
* เนมสเปซ [System::Web](../../)
* Library [Aspose.Slides](../../../)