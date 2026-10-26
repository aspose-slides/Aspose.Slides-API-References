---
title: TransformFinalBlock()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعالج الكتلة الأخيرة من البيانات ويحسب قيمة الإخراج.
type: docs
weight: 14
url: /ar/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) method

يعالج الكتلة الأخيرة من البيانات ويحسب قيمة الإخراج.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البيانات من. |
| inputOffset | int | إزاحة المخزن المؤقت للإدخال. |
| inputCount | int | عدد البايتات التي يجب معالجتها. |

### قيمة الإرجاع

الإخراج المُحسب لكامل تسلسل الإدخال.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [ICryptoTransform](../)
* مساحة اسم [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)