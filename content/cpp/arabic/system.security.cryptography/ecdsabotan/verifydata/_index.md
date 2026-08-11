---
title: VerifyData()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يتحقق من أن توقيع البيانات المحددة صالح.
type: docs
weight: 170
url: /ar/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr&) طريقة


يتحقق من أن توقيع البيانات المحددة صالح.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```


### المعلمات

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | البيانات الموقعة. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. إرجاع true إذا كان التوقيع صالحًا، وإلا - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr&) طريقة


يتحقق من أن توقيع البيانات المحددة صالح.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```


### المعلمات

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | البيانات الموقعة. |
| offset | **int32_t** | الإزاحة في **data**. |
| count | **int32_t** | عدد البايتات التي سيتم تجزئتها. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. إرجاع true إذا كان التوقيع صالحًا، وإلا - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr&) طريقة


يتحقق من أن توقيع الدفق الثنائي المحدد صالح.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```


### المعلمات

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | البيانات الموقعة. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. إرجاع true إذا كان التوقيع صالحًا، وإلا - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) طريقة


يتحقق من أن توقيع البيانات المحددة صالح.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### المعلمات

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | البيانات الموقعة. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع true إذا كان التوقيع صالحًا، وإلا - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) طريقة


يتحقق من أن توقيع البيانات المحددة صالح.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### المعلمات

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | البيانات الموقعة. |
| offset | **int32_t** | الإزاحة في **data**. |
| count | **int32_t** | عدد البايتات التي سيتم تجزئتها. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع true إذا كان التوقيع صالحًا، وإلا - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) طريقة


يتحقق من أن توقيع الدفق الثنائي المحدد صالح.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### المعلمات

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | البيانات الموقعة. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع true إذا كان التوقيع صالحًا، وإلا - false. |

## انظر أيضًا

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)