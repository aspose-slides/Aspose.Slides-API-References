---
title: ToUInt32()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بتحويل أربع بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح غير موقع 32-بت.
type: docs
weight: 105
url: /ar/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) طريقة

يقوم بتحويل أربع بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح غير موقع 32-بت.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) التي تحتوي على البايتات للتحويل |
| startIndex | int | [Index](../../index/) في المصفوفة التي يبدأ منها أخذ البايتات للتحويل |

### قيمة الإرجاع

قيمة عدد صحيح غير موقع 32-بت الناتجة عن التحويل

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) طريقة

يقوم بتحويل أربع بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح غير موقع 32-بت.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView التي تحتوي على البايتات للتحويل |
| startIndex | int | [Index](../../index/) في المصفوفة التي يبدأ منها أخذ البايتات للتحويل |

### قيمة الإرجاع

قيمة عدد صحيح غير موقع 32-بت الناتجة عن التحويل

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* فئة [BitConverter](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)