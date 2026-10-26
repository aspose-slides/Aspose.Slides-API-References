---
title: UrlEncodeToBytes()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เข้ารหัสส่วนของ URI.
type: docs
weight: 66
url: /th/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) เมธอด


เข้ารหัสส่วน URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```


### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | ส่วน URI ที่ต้องการเข้ารหัส. |

### Return Value

ส่วน URI ที่เข้ารหัสแล้ว.

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) เมธอด


เข้ารหัสส่วน URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | ส่วน URI ที่ต้องการเข้ารหัส. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | การเข้ารหัสที่ใช้. |

### Return Value

ส่วน URI ที่เข้ารหัสแล้ว.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) เมธอด


เข้ารหัสส่วน URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | ส่วน URI ที่ต้องการเข้ารหัส. |

### Return Value

ส่วน URI ที่เข้ารหัสแล้ว.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) เมธอด


เข้ารหัสส่วน URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | ส่วน URI ที่ต้องการเข้ารหัส. |
| offset | **int32_t** | ออฟเซ็ตในอาร์เรย์ไบต์ที่กำหนด. |
| count | **int32_t** | จำนวนไบต์ที่จะอ่านจาก. |

### Return Value

ส่วน URI ที่เข้ารหัสแล้ว.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [HttpUtility](../)
* คลาส [Encoding](../../../system.text/encoding/)
* เนมส페ซ [System::Web](../../)
* ไลบรารี [Aspose.Slides](../../../)