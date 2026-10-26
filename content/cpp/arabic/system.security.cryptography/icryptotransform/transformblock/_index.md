---
title: TransformBlock()
second_title: Aspose.Slides ل C++ مرجع API
description: يقوم بمعالجة كتلة من البيانات ونسخ البيانات إلى مصفوفة الإخراج.
type: docs
weight: 1
url: /ar/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) طريقة

يقوم بمعالجة كتلة من البيانات ونسخ البيانات إلى مصفوفة الإخراج.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البيانات منه. |
| inputOffset | int | إزاحة مخزن الإدخال. |
| inputCount | int | عدد البايتات التي سيتم معالجتها. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مخزن الإخراج لنسخ البيانات إليه؛ nullptr لتجنب النسخ. |
| outputOffset | int | إزاحة مخزن الإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## انظر أيضاً

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [ICryptoTransform](../)
* نطاق [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)