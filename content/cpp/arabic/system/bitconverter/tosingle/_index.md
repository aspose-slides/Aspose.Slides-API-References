---
title: ToSingle()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل أربعة بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عائمة بدقة أحادية.
type: docs
weight: 131
url: /ar/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) طريقة

يقوم بتحويل أربعة بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عائمة بدقة أحادية.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) التي تحتوي على البايتات للتحويل |
| startIndex | int | [Index](../../index/) في المصفوفة التي يبدأ عندها أخذ البايتات للتحويل |

### قيمة الإرجاع

قيمة فاصلة عائمة بدقة أحادية ناتجة عن التحويل

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) طريقة

يقوم بتحويل أربعة بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عائمة بدقة أحادية.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView التي تحتوي على البايتات للتحويل |
| startIndex | int | [Index](../../index/) في المصفوفة التي يبدأ عندها أخذ البايتات للتحويل |

### قيمة الإرجاع

قيمة فاصلة عائمة بدقة أحادية ناتجة عن التحويل

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* فئة [BitConverter](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)