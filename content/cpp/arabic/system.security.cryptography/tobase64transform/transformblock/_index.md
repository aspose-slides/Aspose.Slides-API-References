---
title: TransformBlock()
second_title: Aspose.Slides لواجهة برمجة التطبيقات C++
description: يقوم بمعالجة كتلة من البيانات ويقوم بنسخ البيانات إلى مصفوفة الإخراج.
type: docs
weight: 53
url: /ar/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) method

معالجة كتلة من البيانات ونسخ البيانات إلى مصفوفة الإخراج.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البيانات من. |
| inputOffset | **int32_t** | إزاحة مخزن الإدخال. |
| inputCount | **int32_t** | عدد البايتات للمعالجة. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مخزن الإخراج لنسخ البيانات إليه؛ nullptr لعدم النسخ. |
| outputOffset | **int32_t** | إزاحة مخزن الإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ToBase64Transform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)