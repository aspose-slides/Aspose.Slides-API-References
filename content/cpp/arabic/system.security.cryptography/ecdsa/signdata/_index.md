---
title: SignData()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحسب قيمة التجزئة لمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة.
type: docs
weight: 79
url: /ar/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) طريقة

يحسب قيمة التجزئة لمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | مصفوفة البيانات المدخلية. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. تُرجع توقيع ECDSA للبيانات المدخلة. |

## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) طريقة

يحسب قيمة التجزئة لمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | مصفوفة البيانات المدخلية. |
| offset | **int32_t** | الإزاحة في **data**. |
| count | **int32_t** | عدد البايتات المستخدمة كبيانات مدخلية. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. تُرجع توقيع ECDSA للبيانات المدخلة. |

## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) طريقة

يحسب قيمة التجزئة للتيار الثنائي المحدد باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | دفق ثنائي. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. تُرجع توقيع ECDSA للبيانات المدخلة. |

## انظر أيضًا

* تعريف النوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعريف النوع [StreamPtr](../../../system/streamptr/)
* فئة [ECDsa](../)
* بنية [HashAlgorithmName](../../hashalgorithmname/)
* مساحة الأسماء [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)