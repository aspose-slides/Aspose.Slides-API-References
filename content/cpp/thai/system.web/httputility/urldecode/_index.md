---
title: UrlDecode()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ถอดรหัสส่วน URI จากสตริง.
type: docs
weight: 1
url: /th/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) เมธอด

ถอดรหัสส่วน URI จากสตริง.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | [String](../../../system/string/) | ส่วน URI ที่เข้ารหัส. |

### ค่าที่คืนกลับ

ส่วน URI ที่ถอดรหัสแล้ว.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) เมธอด

ถอดรหัสส่วน URI จากสตริง.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | [String](../../../system/string/) | ส่วน URI ที่เข้ารหัส. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | การเข้ารหัสที่จะใช้. |

### ค่าที่คืนกลับ

ส่วน URI ที่ถอดรหัสแล้ว.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) เมธอด

ถอดรหัสส่วน URI จากอาร์เรย์ไบต์.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | ส่วน URI ที่เข้ารหัส. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | การเข้ารหัสที่จะใช้. |

### ค่าที่คืนกลับ

ส่วน URI ที่ถอดรหัสแล้ว.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) เมธอด

ถอดรหัสส่วน URI จากอาร์เรย์ไบต์.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | ส่วน URI ที่เข้ารหัส. |
| offset | **int32_t** | ออฟเซ็ตในอาร์เรย์ไบต์ที่ให้มา. |
| count | **int32_t** | จำนวนไบต์ที่ต้องอ่าน. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | การเข้ารหัสที่จะใช้. |

### ค่าที่คืนกลับ

ส่วน URI ที่ถอดรหัสแล้ว.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [HttpUtility](../)
* คลาส [Encoding](../../../system.text/encoding/)
* เนมสเปซ [System::Web](../../)
* Library [Aspose.Slides](../../../)