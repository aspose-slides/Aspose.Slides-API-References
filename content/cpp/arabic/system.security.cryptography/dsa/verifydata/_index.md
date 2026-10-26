---
title: VerifyData()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يتحقق من أن توقيع البيانات المحددة صالح.
type: docs
weight: 92
url: /ar/system.security.cryptography/dsa/verifydata/
---
## DSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) طريقة

يتحقق من أن توقيع البيانات المحددة صالح.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | البيانات الموقعة. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع true إذا كان التوقيع صالحًا، وإلا false. |

## DSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) طريقة

يتحقق من أن توقيع البيانات المحددة صالح.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | البيانات الموقعة. |
| offset | **int32_t** | الإزShift في **data**. |
| count | **int32_t** | عدد البايتات التي ستُجزَّ. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع true إذا كان التوقيع صالحًا، وإلا false. |

## DSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) طريقة

يتحقق من أن توقيع الدفق الثنائي المحدد صالح.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | البيانات الموقعة. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع true إذا كان التوقيع صالحًا، وإلا false. |

## انظر أيضًا

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* فئة [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* نطاق [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)