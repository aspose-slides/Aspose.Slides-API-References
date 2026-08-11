---
title: Import()
second_title: Aspose.Slides للـ C++ مرجع API
description: يستورد المعلومات من ملف الشهادة المحدد.
type: docs
weight: 300
url: /ar/system.security.cryptography.x509certificates/x509certificate2/import/
---
## X509Certificate2::Import(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) طريقة

يستورد معلومات من ملف الشهادة المحدد.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | اسم ملف الشهادة. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | كلمة المرور المطلوبة للوصول إلى بيانات الشهادة. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&, const String\&, X509KeyStorageFlags) طريقة

يستورد معلومات من ملف الشهادة المحدد.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | اسم ملف الشهادة. |
| password | const [String](../../../system/string/)\& | كلمة المرور المطلوبة للوصول إلى بيانات الشهادة. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) طريقة

يستورد معلومات من بيانات الشهادة المحددة.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | بيانات شهادة X.509. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | كلمة المرور المطلوبة للوصول إلى بيانات الشهادة. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) طريقة

يستورد معلومات من بيانات الشهادة المحددة.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data, const String &password, X509KeyStorageFlags key_storage_flags) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | اسم ملف الشهادة. |
| password | const [String](../../../system/string/)\& | كلمة المرور المطلوبة للوصول إلى بيانات الشهادة. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate2::Import(const String\&) طريقة

يستورد معلومات من ملف الشهادة المحدد.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const String &filename) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | اسم ملف الشهادة. |

## X509Certificate2::Import(const ByteArrayPtr\&) طريقة

يستورد معلومات من بيانات الشهادة المحددة.

```cpp
void System::Security::Cryptography::X509Certificates::X509Certificate2::Import(const ByteArrayPtr &data) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | اسم ملف الشهادة. |

## انظر أيضًا

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* فئة [String](../../../system/string/)
* فئة [X509Certificate2](../)
* نطاق [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)