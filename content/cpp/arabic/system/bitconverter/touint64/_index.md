---
title: ToUInt64()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بتحويل ثمانية بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح غير موقع 64-بت.
type: docs
weight: 118
url: /ar/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) طريقة

يقوم بتحويل ثمانية بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح غير موقع 64-بت.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) التي تحتوي على البايتات للتحويل |
| startIndex | int | [Index](../../index/) في المصفوفة التي يبدأ عندها أخذ البايتات للتحويل |

### قيمة الإرجاع

قيمة عدد صحيح غير موقع 64-بت الناتجة عن التحويل

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) طريقة

يقوم بتحويل ثمانية بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح غير موقع 64-بت.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView التي تحتوي على البايتات للتحويل |
| startIndex | int | [Index](../../index/) في المصفوفة التي يبدأ عندها أخذ البايتات للتحويل |

### قيمة الإرجاع

قيمة عدد صحيح غير موقع 64-بت الناتجة عن التحويل

## انظر أيضًا

* Typedef [ArrayPtr](../../arrayptr/)
* فئة [BitConverter](../)
* مساحة الاسم [System](../../)
* Library [Aspose.Slides](../../../)