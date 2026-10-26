---
title: ToBase64CharArray()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم Base-64 بترميز نطاق من العناصر في مصفوفة البايت المحددة وتخزين البيانات المشفرة كمصفوفة من أحرف Unicode.
type: docs
weight: 27
url: /ar/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) طريقة


يتم ترميز base-64 لنطاق من العناصر في مصفوفة البايت المحددة وتخزين البيانات المشفرة كمصفوفة من أحرف Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```


### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | المصفوفة التي تحتوي على نطاق العناصر التي سيتم ترميزها |
| offset_in | int | فهرس عنصر في المصفوفة الإدخال التي يبدأ عندها النطاق للترميز |
| length | int | طول نطاق العناصر التي سيتم ترميزها |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | مرجع ثابت إلى مصفوفة الإخراج التي سيُوضع فيها البيانات الناتجة |
| offset_out | int | فهرس في مصفوفة الإخراج حيث يبدأ وضع البيانات الناتجة |
| insert_line_breaks | **bool** | يحدد ما إذا كان يجب إدراج أحرف فاصل السطر في مصفوفة الإخراج بعد كل 76 حرفًا من base-64 |

### قيمة الإرجاع

عدد الأحرف المكتوبة إلى مصفوفة الإخراج

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) طريقة


يتم ترميز base-64 لنطاق من العناصر في مصفوفة البايت المحددة وتخزين البيانات المشفرة كمصفوفة من أحرف Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```


### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | المصفوفة التي تحتوي على نطاق العناصر التي سيتم ترميزها |
| offset_in | int | فهرس عنصر في المصفوفة الإدخال التي يبدأ عندها النطاق للترميز |
| length | int | طول نطاق العناصر التي سيتم ترميزها |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | مرجع ثابت إلى مصفوفة الإخراج التي سيُوضع فيها البيانات الناتجة |
| offset_out | int | فهرس في مصفوفة الإخراج حيث يبدأ وضع البيانات الناتجة |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | يحدد خيارات تنسيق البيانات المشفرة بصيغة base-64 |

### قيمة الإرجاع

عدد الأحرف المكتوبة إلى مصفوفة الإخراج

## انظر أيضًا

* عدد [Base64FormattingOptions](../../base64formattingoptions/)
* تعريف نوع [ArrayPtr](../../arrayptr/)
* بنية [Convert](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)