---
title: UrlEncode()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เข้ารหัสส่วนของ URI.
type: docs
weight: 53
url: /th/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) เมธอด


เข้ารหัสส่วนของ URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | [String](../../../system/string/) | ส่วนของ URI ที่ต้องเข้ารหัส. |

### ค่าที่ส่งกลับ

ส่วนของ URI ที่เข้ารหัสแล้ว.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) เมธอด


เข้ารหัสส่วนของ URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | [String](../../../system/string/) | ส่วนของ URI ที่ต้องเข้ารหัส. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | การเข้ารหัสที่ใช้. |

### ค่าที่ส่งกลับ

ส่วนของ URI ที่เข้ารหัสแล้ว.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) เมธอด


เข้ารหัสส่วนของ URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | ส่วนของ URI ที่ต้องเข้ารหัส. |

### ค่าที่ส่งกลับ

ส่วนของ URI ที่เข้ารหัสแล้ว.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด


เข้ารหัสส่วนของ URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | ส่วนของ URI ที่ต้องเข้ารหัส. |
| offset | **int32_t** | ออฟเซ็ตในอาร์เรย์ไบต์ที่กำหนด. |
| count | **int32_t** | จำนวนไบต์ที่จะอ่านจาก. |

### ค่าที่ส่งกลับ

ส่วนของ URI ที่เข้ารหัสแล้ว.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [HttpUtility](../)
* คลาส [Encoding](../../../system.text/encoding/)
* เนมสเปซ [System::Web](../../)
* ไลบรารี [Aspose.Slides](../../../)