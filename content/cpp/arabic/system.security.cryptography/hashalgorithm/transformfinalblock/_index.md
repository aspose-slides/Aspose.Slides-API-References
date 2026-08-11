---
title: TransformFinalBlock()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعالج آخر كتلة من البيانات ويحسب التجزئة.
type: docs
weight: 79
url: /ar/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) طريقة

يعالج آخر كتلة من البيانات ويحسب التجزئة.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البيانات من. |
| inputOffset | int | إزاحة مخزن الإدخال. |
| inputCount | int | عدد البايتات المراد معالجتها. |

### قيمة الإرجاع

Hash calculated for the whole data sequence.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [HashAlgorithm](../)
* مساحة الاسم [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)