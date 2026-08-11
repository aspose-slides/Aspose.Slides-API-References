---
title: X509Certificate()
second_title: مرجع واجهة برمجة التطبيقات لـ Aspose.Slides للغة C++
description: 
type: docs
weight: 1
url: /ar/system.security.cryptography.x509certificates/x509certificate/x509certificate/
---
## X509Certificate::X509Certificate(const X509Certificate\&) منشئ




```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const X509Certificate &)=delete
```

## X509Certificate::X509Certificate() منشئ


منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate()
```

## X509Certificate::X509Certificate(const ByteArrayPtr\&) منشئ


منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &data)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | تسلسل البايتات الذي يمثل شهادة مُرمَّزة. |

## X509Certificate::X509Certificate(const String\&) منشئ


منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | الملف الذي يُحمَّل منه الشهادة. |

## X509Certificate::X509Certificate(const SharedPtr\<X509Certificate\>\&) منشئ


منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const SharedPtr<X509Certificate> &cert)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../)\>\& | شهادة تُستخدم لتهيئة هذا الكائن. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&) منشئ


منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | تسلسل البايتات الذي يمثل شهادة مُرمَّزة. |
| password | const [String](../../../system/string/)\& | كلمة المرور المستخدمة للوصول إلى بيانات الشهادة. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&) منشئ


منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | تسلسل البايتات الذي يمثل شهادة مُرمَّزة. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | كلمة المرور المستخدمة للوصول إلى بيانات الشهادة. |

## X509Certificate::X509Certificate(const String\&, const String\&) منشئ


منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | الملف الذي يُحمَّل منه الشهادة. |
| password | const [String](../../../system/string/)\& | كلمة المرور المستخدمة للوصول إلى بيانات الشهادة. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&) منشئ


منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | الملف الذي يُحمَّل منه الشهادة. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | كلمة المرور المستخدمة للوصول إلى بيانات الشهادة. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) منشئ


منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | تسلسل البايتات الذي يمثل شهادة مُرمَّزة. |
| password | const [String](../../../system/string/)\& | كلمة المرور المستخدمة للوصول إلى بيانات الشهادة. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | العلامات التي تشير إلى كيفية تخزين المفتاح. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) منشئ


منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | تسلسل البايتات الذي يمثل شهادة مُرمَّزة. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | كلمة المرور المستخدمة للوصول إلى بيانات الشهادة. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | العلامات التي تشير إلى كيفية تخزين المفتاح. |

## X509Certificate::X509Certificate(const String\&, const String\&, X509KeyStorageFlags) منشئ


منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | الملف الذي يُحمَّل منه الشهادة. |
| password | const [String](../../../system/string/)\& | كلمة المرور المستخدمة للوصول إلى بيانات الشهادة. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | العلامات التي تشير إلى كيفية تخزين المفتاح. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) منشئ


منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | الملف الذي يُحمَّل منه الشهادة. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | كلمة المرور المستخدمة للوصول إلى بيانات الشهادة. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | العلامات التي تشير إلى كيفية تخزين المفتاح. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) منشئ


منشئ.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | تسلسل البايتات الذي يمثل شهادة مُرمَّزة (الجزء العام). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | تسلسل البايتات الذي يمثل المفتاح الخاص. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | العلامات التي تشير إلى كيفية تخزين المفتاح. |

## انظر أيضًا

* تعداد [X509KeyStorageFlags](../../x509keystorageflags/)
* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [SecureStringPtr](../../../system.security/securestringptr/)
* فئة [X509Certificate](../)
* فئة [String](../../../system/string/)
* مساحة اسم [System::Security::Cryptography::X509Certificates](../../)
* مكتبة [Aspose.Slides](../../../)