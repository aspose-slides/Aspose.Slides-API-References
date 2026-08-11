---
title: VerifyData()
second_title: مرجع API Aspose.Slides للغة C++
description: يفحص توقيع البيانات.
type: docs
weight: 209
url: /ar/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method


يفحص توقيع البيانات.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```


### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) للتحقق من التوقيع. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | التوقيع كما تم استلامه. |

### قيمة الإرجاع

صحيح إذا كان التوقيع صالحًا، خطأ خلاف ذلك.

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


يتحقق من صحة توقيع البيانات المحددة.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات موقعة. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع صحيح إذا كان التوقيع صالحًا، وإلا خطأ. |

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method


يتحقق من صحة توقيع البيانات المحددة.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات موقعة. |
| offset | **int32_t** | الإزاحة في **data**. |
| count | **int32_t** | عدد البايتات التي يجب تجزئتها. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع صحيح إذا كان التوقيع صالحًا، وإلا خطأ. |

## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


يتحقق من صحة توقيع الدفق الثنائي المحدد.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | بيانات موقعة. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات التوقيع. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع صحيح إذا كان التوقيع صالحًا، وإلا خطأ. |

## انظر أيضًا

* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعريف نوع [StreamPtr](../../../system/streamptr/)
* صف [DSACryptoServiceProvider](../)
* بنية [HashAlgorithmName](../../hashalgorithmname/)
* نطاق اسم [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)