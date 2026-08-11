---
title: TransformBlock()
second_title: مرجع API Aspose.Slides للغة C++
description: يعالج كتلة من البيانات وينسخ البيانات إلى مصفوفة الإخراج.
type: docs
weight: 66
url: /ar/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) طريقة

يعالج كتلة من البيانات وينسخ البيانات إلى مصفوفة الإخراج.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```

### معلمات

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البيانات من. |
| inputOffset | int | إزاحة المخزن الإدخالي. |
| inputCount | int | عدد البايتات للمعالجة. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مخزن الإخراج لنسخ البيانات فيه؛ nullptr لعدم النسخ. |
| outputOffset | int | إزاحة مخزن الإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [HashAlgorithm](../)
* نطاق [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)