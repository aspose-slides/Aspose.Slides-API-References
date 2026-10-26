---
title: ToChar()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل بايتين من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة char_t.
type: docs
weight: 40
url: /ar/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) طريقة

يقوم بتحويل بايتين من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة char_t.

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) التي تحتوي على بايتات للتحويل |
| startIndex | int | [Index](../../index/) في المصفوفة التي يبدأ عندها أخذ البايتات للتحويل |

### قيمة الإرجاع

قيمة char_t الناتجة عن التحويل

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) طريقة

يقوم بتحويل بايتين من المصفوفة المحددة بدءًا من الفهرس المحدد إلى قيمة char_t.

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView التي تحتوي على بايتات للتحويل |
| startIndex | int | [Index](../../index/) في المصفوفة التي يبدأ عندها أخذ البايتات للتحويل |

### قيمة الإرجاع

قيمة char_t الناتجة عن التحويل

## انظر أيضًا

* Typedef [ArrayPtr](../../arrayptr/)
* فئة [BitConverter](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)