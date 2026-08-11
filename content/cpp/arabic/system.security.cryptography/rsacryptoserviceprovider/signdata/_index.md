---
title: SignData()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحسب توقيع القيمة المدخلة المحددة.
type: docs
weight: 183
url: /ar/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr&, const SharedPtr<Object>&) طريقة

يحسب توقيع القيمة المدخلة المحددة.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)& | [Buffer](../../../system/buffer/) لقراءة بيانات الإدخال من. |
| halg | const [SharedPtr](../../../system/sharedptr/)<[Object](../../../system/object/)>& | خوارزمية التجزئة للاستخدام. |

### قيمة الإرجاع

[RSA](../../rsa/) توقيع للبيانات المحددة.

## RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream>&, const SharedPtr<Object>&) طريقة

يحسب توقيع القيمة المدخلة المحددة.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)<[IO::Stream](../../../system.io/stream/)>& | دفق لقراءة البيانات الموقعة منه. |
| halg | const [SharedPtr](../../../system/sharedptr/)<[Object](../../../system/object/)>& | خوارزمية التجزئة للاستخدام. |

### قيمة الإرجاع

[RSA](../../rsa/) توقيع للبيانات المحددة.

## RSACryptoServiceProvider::SignData(const ByteArrayPtr&, int32_t, int32_t, const SharedPtr<Object>&) طريقة

يحسب توقيع القيمة المدخلة المحددة.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)& | [Buffer](../../../system/buffer/) لقراءة بيانات الإدخال من. |
| offset | **int32_t** | فهرس بداية شريحة المخزن الإدخال. |
| count | **int32_t** | حجم شريحة مخزن الإدخال. |
| halg | const [SharedPtr](../../../system/sharedptr/)<[Object](../../../system/object/)>& | خوارزمية التجزئة للاستخدام. |

### قيمة الإرجاع

[RSA](../../rsa/) توقيع للبيانات المحددة.

## انظر أيضًا

* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [RSACryptoServiceProvider](../)
* فئة [Stream](../../../system.io/stream/)
* نطاق [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)