---
title: VerifyData()
second_title: Aspose.Slides للغة C++ مرجع API
description: يتحقق من أن توقيع البيانات المحددة صالح.
type: docs
weight: 105
url: /ar/system.security.cryptography/ecdsa/verifydata/
---
## ECDsa::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) طريقة

يتحقق من أن توقيع البيانات المحددة صالح.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | البيانات الموقعة. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع true إذا كان التوقيع صالحًا، وإلا - false. |

## ECDsa::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) طريقة

يتحقق من أن توقيع البيانات المحددة صالح.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | البيانات الموقعة. |
| offset | **int32_t** | الإزاحة في **data**. |
| count | **int32_t** | عدد البايتات لتجزئتها. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع true إذا كان التوقيع صالحًا، وإلا - false. |

## ECDsa::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) طريقة

يتحقق من أن توقيع تدفق البيانات الثنائي المحدد صالح.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | البيانات الموقعة. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع true إذا كان التوقيع صالحًا، وإلا - false. |

## انظر أيضًا

* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعريف نوع [StreamPtr](../../../system/streamptr/)
* فئة [ECDsa](../)
* بنية [HashAlgorithmName](../../hashalgorithmname/)
* نطاق [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)