---
title: UrlDecode()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يقوم بفك ترميز مقطع URI من السلسلة.
type: docs
weight: 1
url: /ar/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) طريقة

يفك ترميز ش fragment URI من سلسلة.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | [String](../../../system/string/) | ش fragment URI المشفر. |

### قيمة الإرجاع

ش fragment URI المفكك.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) طريقة

يفك ترميز ش fragment URI من سلسلة.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | [String](../../../system/string/) | ش fragment URI المشفر. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | الترميز المستخدم. |

### قيمة الإرجاع

ش fragment URI المفكك.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) طريقة

يفك ترميز ش fragment URI من مصفوفة بايتات.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | ش fragment URI المشفر. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | الترميز المستخدم. |

### قيمة الإرجاع

ش fragment URI المفكك.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) طريقة

يفك ترميز ش fragment URI من مصفوفة بايتات.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | ش fragment URI المشفر. |
| offset | **int32_t** | الإزاحة في مصفوفة البايتات المعطاة. |
| count | **int32_t** | عدد البايتات التي يجب قراءتها من. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | الترميز المستخدم. |

### قيمة الإرجاع

ش fragment URI المفكك.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [HttpUtility](../)
* فئة [Encoding](../../../system.text/encoding/)
* نطاق [System::Web](../../)
* مكتبة [Aspose.Slides](../../../)