---
title: SignData()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحسب قيمة التجزئة للمصفوفة البيانات المحددة، ويوقع النتيجة.
type: docs
weight: 131
url: /ar/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) طريقة

يحسب قيمة التجزئة للمصفوفة البيانات المحددة، ويوقع النتيجة.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | مصفوفة بيانات الإدخال. إرجاع توقيع ECDSA للبيانات المدخلة. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) طريقة

يحسب قيمة التجزئة للمصفوفة البيانات المحددة، ويوقع النتيجة.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | مصفوفة بيانات الإدخال. |
| offset | **int32_t** | الإزاحة في **data**. |
| count | **int32_t** | عدد البايتات المستخدمة كبيانات إدخال. إرجاع توقيع ECDSA للبيانات المدخلة. |

## ECDsaBotan::SignData(const StreamPtr\&) طريقة

يحسب قيمة التجزئة لتيار البيانات الثنائي المحدد، ويوقع النتيجة.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | تيار ثنائي. إرجاع توقيع ECDSA للبيانات المدخلة. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) طريقة

يحسب قيمة التجزئة للمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | مصفوفة بيانات الإدخال. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع توقيع ECDSA للبيانات المدخلة. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) طريقة

يحسب قيمة التجزئة للمصفوفة البيانات المحددة باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | مصفوفة بيانات الإدخال. |
| offset | **int32_t** | الإزاحة في **data**. |
| count | **int32_t** | عدد البايتات المستخدمة كبيانات إدخال. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع توقيع ECDSA للبيانات المدخلة. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) طريقة

يحسب قيمة التجزئة لتيار البيانات الثنائي المحدد باستخدام خوارزمية التجزئة المحددة، ويوقع النتيجة.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | تيار ثنائي. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | خوارزمية التجزئة. إرجاع توقيع ECDSA للبيانات المدخلة. |

## انظر أيضًا

* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعريف نوع [StreamPtr](../../../system/streamptr/)
* فئة [ECDsaBotan](../)
* بنية [HashAlgorithmName](../../hashalgorithmname/)
* مساحة أسماء [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)