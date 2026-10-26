---
title: ComputeHash()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بتجزئة الذاكرة المؤقتة.
type: docs
weight: 14
url: /ar/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) طريقة

يقوم بإنشاء تجزئة للذاكرة المؤقتة.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المخزن المؤقت المصدر. |

### قيمة الإرجاع

قيمة التجزئة المحسوبة.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) طريقة

يقوم بإنشاء تجزئة لجزء من الذاكرة المؤقتة.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المخزن المؤقت المصدر. |
| offset | int | الإزاحة في المخزن المؤقت المصدر. |
| count | int | عدد البايتات المستخدمة من المخزن المؤقت المصدر. |

### قيمة الإرجاع

قيمة التجزئة المحسوبة.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) طريقة

يقرأ الدفق حتى النهاية ويحسب التجزئة للبيانات المقروءة.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | الدفق لقراءة البيانات منه. |

### قيمة الإرجاع

قيمة التجزئة المحسوبة لكامل بيانات الدفق.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)