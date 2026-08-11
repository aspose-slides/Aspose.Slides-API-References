---
title: X509Certificate2()
second_title: Aspose.Slides لمرجع API لـ C++
description: ينشئ X509Certificate2 فارغًا.
type: docs
weight: 1
url: /ar/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() المنشئ

ينشئ فارغًا [X509Certificate2](../).

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) المنشئ

المنشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | ملف لتحميل الشهادة منه. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) المنشئ

المنشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | كائن [X509Certificate](../../x509certificate/). |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) المنشئ

المنشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | تسلسل من البايتات يمثل الشهادة المشفرة. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) المنشئ

المنشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | تسلسل من البايتات يمثل الشهادة المشفرة. |
| password | const [String](../../../system/string/)\& | كلمة مرور الشهادة. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) المنشئ

المنشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | تسلسل من البايتات يمثل الشهادة المشفرة. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | كلمة مرور الشهادة. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) المنشئ

المنشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | تسلسل من البايتات يمثل الشهادة المشفرة. |
| password | const [String](../../../system/string/)\& | كلمة مرور الشهادة. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | علامات تُشير إلى كيفية تخزين المفتاح. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) المنشئ

المنشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | تسلسل من البايتات يمثل الشهادة المشفرة. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | كلمة مرور الشهادة. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | علامات تُشير إلى كيفية تخزين المفتاح. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) المنشئ

المنشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | ملف لتحميل الشهادة منه. |
| password | const [String](../../../system/string/)\& | كلمة مرور الشهادة. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) المنشئ

المنشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | ملف لتحميل الشهادة منه. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | كلمة مرور الشهادة. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) المنشئ

المنشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | ملف لتحميل الشهادة منه. |
| password | const [String](../../../system/string/)\& | كلمة مرور الشهادة. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | علامات تُشير إلى كيفية تخزين المفتاح. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) المنشئ

المنشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | ملف لتحميل الشهادة منه. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | كلمة مرور الشهادة. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | علامات تُشير إلى كيفية تخزين المفتاح. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) المنشئ

المنشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | تسلسل من البايتات يمثل الشهادة المشفرة (الجزء العام). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | تسلسل من البايتات يمثل المفتاح الخاص. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | علامات تُشير إلى كيفية تخزين المفتاح. |

## انظر أيضًا

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)