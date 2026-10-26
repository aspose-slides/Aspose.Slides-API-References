---
title: ToUInt16()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بتحويل بايتين من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح غير موقّع 16 بت.
type: docs
weight: 92
url: /ar/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) طريقة

يقوم بتحويل بايتين من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح غير موقّع 16 بت.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) التي تحتوي على البايتات للتحويل |
| startIndex | int | [Index](../../index/) في المصفوفة التي يبدأ عندها أخذ البايتات للتحويل |

### قيمة الإرجاع

قيمة عدد صحيح غير موقّع 16 بت ناتجة عن التحويل

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) طريقة

يقوم بتحويل بايتين من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح غير موقّع 16 بت.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView التي تحتوي على البايتات للتحويل |
| startIndex | int | [Index](../../index/) في المصفوفة التي يبدأ عندها أخذ البايتات للتحويل |

### قيمة الإرجاع

قيمة عدد صحيح غير موقّع 16 بت ناتجة عن التحويل

## انظر أيضًا

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)