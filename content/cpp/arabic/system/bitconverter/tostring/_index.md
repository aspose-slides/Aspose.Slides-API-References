---
title: ToString()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بتحويل جميع قيم مصفوفة البايت المحددة إلى تمثيلها السلسلي الست عشري. يتم تحديد حالة الأحرف المستخدمة في التدوين الست عشري والفاصل المدرج بين كل زوج من البايتات المتجاورة من خلال المعلمات المقابلة.
type: docs
weight: 157
url: /ar/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) طريقة


يقوم بتحويل جميع قيم مصفوفة البايت المحددة إلى تمثيلها السلسلي الست عشري. حالة الأحرف المستخدمة في التدوين الست عشري والفاصل المُدرج بين كل زوج من البايتات المتجاورة يتم تحديدهما من خلال المعلمات المقابلة.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) التي تحتوي على البايتات التي سيتم تحويلها |
| uppercase | **bool** | يحدد حالة الأحرف المستخدمة في التمثيل الست عشري الناتج |
| separator | const [String](../../string/)\& | سلسلة تُستخدم كفاصل يُدرج بين كل زوج من البايتات المتجاورة في السلسلة الناتجة |

### قيمة الإرجاع

[String](../../string/) التي تحتوي على تمثيل ست عشري لمصفوفة البايت المحددة

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) طريقة


يقوم بتحويل قيم مصفوفة البايت المحددة إلى تمثيلها السلسلي الست عشري بدءًا من الفهرس المحدد.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) التي تحتوي على البايتات التي سيتم تحويلها |
| startIndex | int | [Index](../../index/) في المصفوفة المحددة التي يبدأ عندها التحويل |

### قيمة الإرجاع

[String](../../string/) التي تحتوي على تمثيل ست عشري للنطاق المحدد من عناصر المصفوفة المحددة

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) طريقة


يقوم بتحويل نطاق من قيم مصفوفة البايت المحددة إلى تمثيلها السلسلي الست عشري.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```


### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) التي تحتوي على البايتات التي سيتم تحويلها |
| startIndex | int | [Index](../../index/) في المصفوفة المحددة التي يبدأ عنده نطاق عناصر مصفوفة البايت التي سيتم تحويلها |
| length | int | طول النطاق لعناصر مصفوفة البايت التي سيتم تحويلها |

### قيمة الإرجاع

[String](../../string/) التي تحتوي على تمثيل ست عشري للنطاق المحدد من عناصر المصفوفة المحددة

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* فئة [String](../../string/)
* فئة [BitConverter](../)
* فضاء الأسماء [System](../../)
* مكتبة [Aspose.Slides](../../../)