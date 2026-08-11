---
title: HashData()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: يحسب قيمة التجزئة لمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة.
type: docs
weight: 105
url: /ar/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) طريقة

يحسب قيمة التجزئة لمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```

### المعاملات

| المعرف | النوع | الوصف |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) لتجزئة. |
| offset | **int32_t** | الإزاحة في **data**. |
| count | **int32_t** | عدد البايتات لتجزئة. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | خوارزمية التجزئة. |

### قيمة الإرجاع

بيانات مجزأة.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) طريقة

يحسب قيمة التجزئة لتدفق البيانات الثنائي المحدد باستخدام خوارزمية التجزئة المحددة.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```

### المعاملات

| المعرف | النوع | الوصف |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | تدفق ثنائي لتجزئة. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | خوارزمية التجزئة. |

### قيمة الإرجاع

بيانات مجزأة.

## انظر أيضًا

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)