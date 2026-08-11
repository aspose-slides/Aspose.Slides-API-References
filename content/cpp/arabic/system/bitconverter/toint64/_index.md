---
title: ToInt64()
second_title: Aspose.Slides للغة C++ مرجع API
description: يحوّل ثمانية بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح 64-بت.
type: docs
weight: 79
url: /ar/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) طريقة

تحويل ثمانية بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح 64-بت.

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) التي تحتوي على بايتات للتحويل |
| startIndex | int | [Index](../../index/) في المصفوفة التي يبدأ عندها أخذ البايتات للتحويل |

### قيمة الإرجاع

قيمة عدد صحيح 64-بت ناتجة عن التحويل

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) طريقة

تحويل ثمانية بايتات من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة عدد صحيح 64-بت.

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView التي تحتوي على بايتات للتحويل |
| startIndex | int | [Index](../../index/) في المصفوفة التي يبدأ عندها أخذ البايتات للتحويل |

### قيمة الإرجاع

قيمة عدد صحيح 64-بت ناتجة عن التحويل

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* فئة [BitConverter](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)