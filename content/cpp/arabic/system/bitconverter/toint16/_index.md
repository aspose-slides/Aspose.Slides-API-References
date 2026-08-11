---
title: ToInt16()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تحول بايتين من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح 16-بت.
type: docs
weight: 53
url: /ar/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) طريقة

يتحول بايتين من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح 16-بت.

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) التي تحتوي على البايتات للتحويل |
| startIndex | int | [Index](../../index/) في المصفوفة التي يبدأ فيها أخذ البايتات للتحويل |

### قيمة الإرجاع

قيمة عدد صحيح 16-بت الناتجة عن التحويل

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) طريقة

يتحول بايتين من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح 16-بت.

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView التي تحتوي على البايتات للتحويل |
| startIndex | int | [Index](../../index/) في المصفوفة التي يبدأ فيها أخذ البايتات للتحويل |

### قيمة الإرجاع

قيمة عدد صحيح 16-بت الناتجة عن التحويل

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* الفئة [BitConverter](../)
* مساحة الاسم [System](../../)
* المكتبة [Aspose.Slides](../../../)