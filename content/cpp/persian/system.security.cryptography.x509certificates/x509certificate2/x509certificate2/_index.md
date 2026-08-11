---
title: X509Certificate2()
second_title: مرجع API Aspose.Slides برای C++
description: یک X509Certificate2 خالی می‌سازد.
type: docs
weight: 1
url: /fa/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() سازنده

یک [X509Certificate2](../) خالی می‌سازد.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) سازنده

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | فایلی که گواهی از آن بارگذاری می‌شود. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) سازنده

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | یک شیء از نوع [X509Certificate](../../x509certificate/). |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) سازنده

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دنباله‌ای از بایت‌ها که گواهی رمزگذاری‌شده را نشان می‌دهد. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) سازنده

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دنباله‌ای از بایت‌ها که گواهی رمزگذاری‌شده را نشان می‌دهد. |
| password | const [String](../../../system/string/)\& | رمز عبور گواهی. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) سازنده

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دنباله‌ای از بایت‌ها که گواهی رمزگذاری‌شده را نشان می‌دهد. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | رمز عبور گواهی. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) سازنده

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دنباله‌ای از بایت‌ها که گواهی رمزگذاری‌شده را نشان می‌دهد. |
| password | const [String](../../../system/string/)\& | رمز عبور گواهی. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | پرچم‌هایی که نشان‌دهنده نحوه ذخیره‌سازی کلید هستند. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) سازنده

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دنباله‌ای از بایت‌ها که گواهی رمزگذاری‌شده را نشان می‌دهد. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | رمز عبور گواهی. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | پرچم‌هایی که نشان‌دهنده نحوه ذخیره‌سازی کلید هستند. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) سازنده

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | فایلی که گواهی از آن بارگذاری می‌شود. |
| password | const [String](../../../system/string/)\& | رمز عبور گواهی. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) سازنده

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | فایلی که گواهی از آن بارگذاری می‌شود. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | رمز عبور گواهی. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) سازنده

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | فایلی که گواهی از آن بارگذاری می‌شود. |
| password | const [String](../../../system/string/)\& | رمز عبور گواهی. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | پرچم‌هایی که نشان‌دهنده نحوه ذخیره‌سازی کلید هستند. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) سازنده

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | فایلی که گواهی از آن بارگذاری می‌شود. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | رمز عبور گواهی. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | پرچم‌هایی که نشان‌دهنده نحوه ذخیره‌سازی کلید هستند. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) سازنده

سازنده.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دنباله‌ای از بایت‌ها که گواهی رمزگذاری‌شده (قسمت عمومی) را نشان می‌دهد. |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دنباله‌ای از بایت‌ها که کلید خصوصی را نشان می‌دهد. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | پرچم‌هایی که نشان‌دهنده نحوه ذخیره‌سازی کلید هستند. |

## موارد مرتبط

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)