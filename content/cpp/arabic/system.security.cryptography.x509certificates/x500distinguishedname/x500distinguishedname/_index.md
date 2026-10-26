---
title: X500DistinguishedName()
second_title: Aspose.Slides لـ C++ دليل API
description: منشئ.
type: docs
weight: 1
url: /ar/system.security.cryptography.x509certificates/x500distinguishedname/x500distinguishedname/
---
## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<AsnEncodedData\>\&) constructor

منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<AsnEncodedData> &encoded_distinguished_name)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| encoded_distinguished_name | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | [Object](../../../system/object/) تمثّل الاسم المميز. |

## X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr\&) constructor

منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr &encoded_distinguished_name)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| encoded_distinguished_name | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | الاسم المميز المشفّر. |

## X500DistinguishedName::X500DistinguishedName(const String\&) constructor

منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | الاسم المميز. |

## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<X500DistinguishedName\>\&) constructor

منشئ نسخة.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<X500DistinguishedName> &distinguishedName)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| distinguishedName | const [SharedPtr](../../../system/sharedptr/)\<[X500DistinguishedName](../)\>\& | الاسم المميز لنسخ البيانات منه. |

## X500DistinguishedName::X500DistinguishedName(const String\&, X500DistinguishedNameFlags) constructor

منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name, X500DistinguishedNameFlags flags)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | الاسم المميز. |
| flags | [X500DistinguishedNameFlags](../../x500distinguishednameflags/) | العلامات المدمجة بالبت لتحديد خصائص بناء الاسم. |

## انظر أيضًا

* تعداد [X500DistinguishedNameFlags](../../x500distinguishednameflags/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* فئة [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* فئة [X500DistinguishedName](../)
* فئة [String](../../../system/string/)
* نطاق [System::Security::Cryptography::X509Certificates](../../)
* مكتبة [Aspose.Slides](../../../)