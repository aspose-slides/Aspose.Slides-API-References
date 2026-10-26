---
title: ConvertToUtf32()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل زوج الإفلات UTF-16 المحدد إلى وحدة شفرة UTF-32.
type: docs
weight: 287
url: /ar/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) طريقة


يقوم بتحويل زوج الإفلات UTF-16 المحدد إلى وحدة شفرة UTF-32.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```


### المعطيات

| Parameter | Type | Description |
| --- | --- | --- |
| highSurrogate | char_t | المقابل العالي لزوج الإفلات UTF-16 المراد تحويله |
| lowSurrogate | char_t | المقابل المنخفض لزوج الإفلات UTF-16 المراد تحويله |

### قيمة الإرجاع

وحدة شفرة UTF-32 الناتجة عن التحويل

## Char::ConvertToUtf32(const String\&, int) طريقة


يقوم بتحويل قيمة حرف UTF-16 مشفر أو زوج إفلات في موقع محدد داخل سلسلة إلى وحدة شفرة UTF-32.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```


### المعطيات

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | سلسلة تحتوي على حرف أو زوج إفلات |
| index | int | موضع الفهرس للحرف أو زوج الإفلات في السلسلة المحددة |

### قيمة الإرجاع

وحدة شفرة UTF-32 الناتجة عن التحويل

## أنظر أيضًا

* الفئة [Char](../)
* الفئة [String](../../string/)
* مساحة الاسم [System](../../)
* المكتبة [Aspose.Slides](../../../)