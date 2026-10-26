---
title: GetCertContentType()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على نوع الشهادة الموجودة في مصفوفة البايت المحددة.
type: docs
weight: 391
url: /ar/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) طريقة

يحصل على نوع الشهادة الموجودة في مصفوفة البايت المحددة.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات الشهادة. |

### قيمة الإرجاع

نوع شهادة X.509.

## X509Certificate2::GetCertContentType(const String\&) طريقة

يحصل على نوع الشهادة الموجودة في الملف المحدد.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | اسم ملف الشهادة. |

### قيمة الإرجاع

نوع شهادة X.509.

## انظر أيضاً

* تعداد [X509ContentType](../../x509contenttype/)
* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* فئة [X509Certificate2](../)
* فئة [String](../../../system/string/)
* مساحة الاسم [System::Security::Cryptography::X509Certificates](../../)
* مكتبة [Aspose.Slides](../../../)