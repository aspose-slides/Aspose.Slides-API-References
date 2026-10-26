---
title: SignData()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحسب التوقيع للقيمة المدخلة المحددة.
type: docs
weight: 183
url: /ar/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) طريقة

يحسب التوقيع للقيمة المدخلة المحددة.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) لقراءة البيانات المدخلة من. |

### قيمة الإرجاع

[DSA](../../dsa/) توقيع للبيانات المحددة.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) طريقة

يحسب التوقيع للقيمة المدخلة المحددة.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | دفق لقراءة البيانات التي يتم توقيعها من. |

### قيمة الإرجاع

[DSA](../../dsa/) توقيع للبيانات المحددة.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) طريقة

يحسب التوقيع للقيمة المدخلة المحددة.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) لقراءة البيانات المدخلة من. |
| offset | **int32_t** | فهرس بداية شريحة مخزن الإدخال. |
| count | **int32_t** | حجم شريحة مخزن الإدخال. |

### قيمة الإرجاع

[DSA](../../dsa/) توقيع للبيانات المحددة.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) طريقة

يحسب قيمة التجزئة لمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة، ثم يوقع النتيجة.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | مصفوفة البيانات المدخلة. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع [DSA](../../dsa/) توقيع للبيانات المدخلة. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) طريقة

يحسب قيمة التجزئة لمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة، ثم يوقع النتيجة.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | مصفوفة البيانات المدخلة. |
| offset | **int32_t** | الإزاحة في **data**. |
| count | **int32_t** | عدد البايتات لاستخدامها كبيانات مدخلة. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع [DSA](../../dsa/) توقيع للبيانات المدخلة. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) طريقة

يحسب قيمة التجزئة للدفقة الثنائية المحددة باستخدام خوارزمية التجزئة المحددة، ثم يوقع النتيجة.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | دفق ثنائي. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع [DSA](../../dsa/) توقيع للبيانات المدخلة. |

## أنظر أيضًا

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* فئة [DSACryptoServiceProvider](../)
* فئة [Stream](../../../system.io/stream/)
* بنية [HashAlgorithmName](../../hashalgorithmname/)
* نطاق الاسم [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)