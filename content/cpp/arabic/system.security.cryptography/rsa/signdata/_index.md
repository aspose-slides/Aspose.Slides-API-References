---
title: SignData()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحسب قيمة التجزئة لصفيف البيانات المحدد باستخدام خوارزمية التجزئة والتعبئة المحددة، ويوقع النتيجة.
type: docs
weight: 131
url: /ar/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) طريقة

يحسب قيمة التجزئة لصفيف البيانات المحدد باستخدام خوارزمية التجزئة وتعبئة المحددة، ويوقع النتيجة.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | صفيف البيانات المدخل. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | وضع الحشو. إرجاع التوقيع [RSA](../) للبيانات المدخلية. |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) طريقة

يحسب قيمة التجزئة لصفيف البيانات المحدد باستخدام خوارزمية التجزئة وتعبئة المحددة، ويوقع النتيجة.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | صفيف البيانات المدخل. |
| offset | **int32_t** | الإزاحة في **data**. |
| count | **int32_t** | عدد البايتات المستخدمة كبيانات مدخل. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | وضع الحشو. إرجاع التوقيع [RSA](../) للبيانات المدخلية. |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) طريقة

يحسب قيمة التجزئة للدفق الثنائي المحدد باستخدام خوارزمية التجزئة وتعبئة المحددة، ويوقع النتيجة.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | دفق ثنائي. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | وضع الحشو. إرجاع التوقيع [RSA](../) للبيانات المدخلية. |

## انظر أيضاً

* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [StreamPtr](../../../system/streamptr/)
* فئة [RSASignaturePadding](../../rsasignaturepadding/)
* فئة [RSA](../)
* بنية [HashAlgorithmName](../../hashalgorithmname/)
* مساحة أسماء [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)