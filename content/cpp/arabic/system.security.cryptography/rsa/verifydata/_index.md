---
title: VerifyData()
second_title: مرجع API Aspose.Slides للغة C++
description: يتحقق من أن توقيع البيانات المحددة صالح.
type: docs
weight: 157
url: /ar/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) طريقة


يتحقق من أن توقيع البيانات المحددة صالح.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | البيانات الموقعة. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | وضع الحشو. إرجاع true إذا كان التوقيع صالحًا، وإلا - false. |

## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) طريقة


يتحقق من أن توقيع البيانات المحددة صالح.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | البيانات الموقعة. |
| offset | **int32_t** | الإزاحة في data. |
| count | **int32_t** | عدد البايتات للتجزئة. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | وضع الحشو. إرجاع true إذا كان التوقيع صالحًا، وإلا - false. |

## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) طريقة


يتحقق من أن توقيع الدفق الثنائي المحدد صالح.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | البيانات الموقعة. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | وضع الحشو. إرجاع true إذا كان التوقيع صالحًا، وإلا - false. |

## انظر أيضًا

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)