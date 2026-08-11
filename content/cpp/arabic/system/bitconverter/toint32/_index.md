---
title: ToInt32()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تحوّل أربعة بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح 32-بت.
type: docs
weight: 66
url: /ar/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) طريقة

تحوّل أربعة بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح 32-بت.

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) التي تحتوي على البايتات للتحويل |
| startIndex | int | [Index](../../index/) في المصفوفة التي يبدأ عندها أخذ البايتات للتحويل |

### قيمة الإرجاع

قيمة عدد صحيح 32-بت ناتجة عن التحويل

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) طريقة

تحوّل أربعة بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح 32-بت.

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView التي تحتوي على البايتات للتحويل |
| startIndex | int | [Index](../../index/) في المصفوفة التي يبدأ عندها أخذ البايتات للتحويل |

### قيمة الإرجاع

قيمة عدد صحيح 32-بت ناتجة عن التحويل

## انظر أيضًا

* Typedef [ArrayPtr](../../arrayptr/)
* فئة [BitConverter](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)