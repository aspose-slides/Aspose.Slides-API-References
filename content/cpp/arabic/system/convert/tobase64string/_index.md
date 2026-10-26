---
title: ToBase64String()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم Base-64 بترميز العناصر في مصفوفة البايت المحددة ويعيد البيانات المشفرة كسلسلة.
type: docs
weight: 40
url: /ar/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) طريقة

يقوم Base-64 بترميز العناصر في مصفوفة البايت المحددة ويعيد البيانات المشفرة كسلسلة.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```

### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | مصفوفة البايتات التي سيتم ترميزها |
| insert_line_breaks | **bool** | يحدد ما إذا كان يجب إدراج أحرف فاصل السطر في سلسلة الإخراج بعد كل 76 حرفًا من Base-64 |

### قيمة الإرجاع

السلسلة التي تحتوي على تمثيل Base-64 المشفر لمصفوفة الإدخال

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) طريقة

يقوم Base-64 بترميز نطاق من العناصر في مصفوفة البايت المحددة ويعيد البيانات المشفرة كسلسلة.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```

### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | مصفوفة البايتات التي تحتوي على نطاق العناصر التي سيتم ترميزها |
| offset_in | int | فهرس عنصر في مصفوفة الإدخال حيث يبدأ النطاق المراد ترميزه |
| length | int | طول نطاق العناصر التي سيتم ترميزها |
| insert_line_breaks | **bool** | يحدد ما إذا كان يجب إدراج أحرف فاصل السطر في سلسلة الإخراج بعد كل 76 حرفًا من Base-64 |

### قيمة الإرجاع

السلسلة التي تحتوي على تمثيل Base-64 المشفر لنطاق العناصر من مصفوفة الإدخال

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) طريقة

يقوم Base-64 بترميز العناصر في مصفوفة البايت المحددة ويعيد البيانات المشفرة كسلسلة.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```

### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | مصفوفة البايتات التي سيتم ترميزها |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | يحدد خيارات تنسيق البيانات المشفرة بـ Base-64 |

### قيمة الإرجاع

السلسلة التي تحتوي على تمثيل Base-64 المشفر لمصفوفة الإدخال

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) طريقة

يقوم Base-64 بترميز نطاق من العناصر في مصفوفة البايت المحددة ويعيد البيانات المشفرة كسلسلة.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```

### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | مصفوفة البايتات التي تحتوي على نطاق العناصر التي سيتم ترميزها |
| offset_in | int | فهرس عنصر في مصفوفة الإدخال حيث يبدأ النطاق المراد ترميزه |
| length | int | طول نطاق العناصر التي سيتم ترميزها |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | يحدد خيارات تنسيق البيانات المشفرة بـ Base-64 |

### قيمة الإرجاع

السلسلة التي تحتوي على تمثيل Base-64 المشفر لنطاق العناصر من مصفوفة الإدخال

## انظر أيضًا

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)