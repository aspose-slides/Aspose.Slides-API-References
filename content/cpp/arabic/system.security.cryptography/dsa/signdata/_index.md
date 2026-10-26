---
title: SignData()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحسب قيمة التجزئة لمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة.
type: docs
weight: 79
url: /ar/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) طريقة

يحسب قيمة التجزئة لمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | مصفوفة البيانات المدخلة. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع التوقيع [DSA](../) للبيانات المدخلة. |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) طريقة

يحسب قيمة التجزئة لمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | مصفوفة البيانات المدخلة. |
| offset | **int32_t** | إزاحة في **data**. |
| count | **int32_t** | عدد البايتات المستخدمة كبيانات مدخلة. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع التوقيع [DSA](../) للبيانات المدخلة. |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) طريقة

يحسب قيمة التجزئة للتيار الثنائي المحدد باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | التيار الثنائي. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع التوقيع [DSA](../) للبيانات المدخلة. |

## انظر أيضًا

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* فئة [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* نطاق [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)