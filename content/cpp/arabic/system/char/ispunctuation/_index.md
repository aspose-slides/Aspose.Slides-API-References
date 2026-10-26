---
title: IsPunctuation()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد ما إذا كان الحرف الموجود في الفهرس المحدد داخل مخزن الأحرف المحدد يُصنّف كحرف علامات ترقيم.
type: docs
weight: 209
url: /ar/system/char/ispunctuation/
---
## Char::IsPunctuation(const char_t *, int) طريقة


يحدد ما إذا كان الحرف الموجود في الفهرس المحدد داخل مخزن الأحرف المحدد يُصنّف كحرف علامات ترقيم.

```cpp
static bool System::Char::IsPunctuation(const char_t *str, int idx)
```


### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char_t * | مؤشر إلى بداية مخزن الأحرف |
| idx | int | فهرس يبدأ من الصفر في المخزن المحدد للحرف الذي سيتم اختباره |

### قيمة الإرجاع

صحيح إذا كان الحرف في الفهرس المحدد هو حرف علامات ترقيم، وإلا - خطأ

## Char::IsPunctuation(char_t) طريقة


يحدد ما إذا كان الحرف المحدد يُصنّف كحرف علامات ترقيم.

```cpp
static bool System::Char::IsPunctuation(char_t c)
```


### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | الحرف الذي سيتم اختباره |

### قيمة الإرجاع

صحيح إذا كان الحرف المحدد هو حرف علامات ترقيم، وإلا - خطأ

## انظر أيضًا

* الفئة [Char](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)