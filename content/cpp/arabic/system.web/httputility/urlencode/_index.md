---
title: UrlEncode()
second_title: Aspose.Slides لمرجع API لـ C++
description: يقوم بترميز جزء URI.
type: docs
weight: 53
url: /ar/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) الطريقة

يقوم بترميز جزء URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | [String](../../../system/string/) | جزء URI للترميز. |

### قيمة الإرجاع

جزء URI المشفر.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) الطريقة

يقوم بترميز جزء URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | [String](../../../system/string/) | جزء URI للترميز. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | الترميز المستخدم. |

### قيمة الإرجاع

جزء URI المشفر.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) الطريقة

يقوم بترميز جزء URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | جزء URI للترميز. |

### قيمة الإرجاع

جزء URI المشفر.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) الطريقة

يقوم بترميز جزء URI.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | جزء URI للترميز. |
| offset | **int32_t** | الإزاحة في مصفوفة البايتات المعطاة. |
| count | **int32_t** | عدد البايتات التي يتم قراءتها. |

### قيمة الإرجاع

جزء URI المشفر.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* الفئة [String](../../../system/string/)
* الفئة [HttpUtility](../)
* الفئة [Encoding](../../../system.text/encoding/)
* نطاق الاسم [System::Web](../../)
* المكتبة [Aspose.Slides](../../../)