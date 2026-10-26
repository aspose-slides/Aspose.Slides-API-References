---
title: UrlDecodeToBytes()
second_title: مرجع API Aspose.Slides للغة C++
description: يفك ترميز جزء URI من مصفوفة بايت.
type: docs
weight: 14
url: /ar/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) طريقة

يفك ترميز جزء URI من مصفوفة بايت.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | جزء URI المشفر. |

### قيمة الإرجاع

جزء URI المفك ترميزه.

## HttpUtility::UrlDecodeToBytes(const String\&) طريقة

يفك ترميز جزء URI من سلسلة بايت.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | جزء URI المشفر. |

### قيمة الإرجاع

جزء URI المفك ترميزه.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) طريقة


يفك ترميز جزء URI من نص.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | جزء URI المشفر. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | الترميز المستخدم. |

### قيمة الإرجاع

جزء URI المفك ترميزه.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة


يفك ترميز جزء URI من مصفوفة بايت.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### المعطيات

| المع معامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | جزء URI المشفر. |
| offset | **int32_t** | الإزاحة في مصفوفة البايت المعطاة. |
| count | **int32_t** | عدد البايتات التي سيُقرأ منها. |

### قيمة الإرجاع

جزء URI المفك ترميزه.

## انظر أيضاً

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [HttpUtility](../)
* فئة [String](../../../system/string/)
* فئة [Encoding](../../../system.text/encoding/)
* نطاق الاسم [System::Web](../../)
* مكتبة [Aspose.Slides](../../../)