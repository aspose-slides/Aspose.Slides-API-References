---
title: X509Certificate()
second_title: Aspose.Slides for C++ API Referansı
description: 
type: docs
weight: 1
url: /tr/system.security.cryptography.x509certificates/x509certificate/x509certificate/
---
## X509Certificate::X509Certificate(const X509Certificate\&) yapıcı




```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const X509Certificate &)=delete
```

## X509Certificate::X509Certificate() yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate()
```

## X509Certificate::X509Certificate(const ByteArrayPtr\&) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &data)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodlanmış sertifikayı temsil eden bayt dizisi. |

## X509Certificate::X509Certificate(const String\&) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Sertifikanın yükleneceği dosya. |

## X509Certificate::X509Certificate(const SharedPtr\<X509Certificate\>\&) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const SharedPtr<X509Certificate> &cert)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../)\>\& | Bu nesneyi başlatmak için kullanılan bir sertifika. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodlanmış sertifikayı temsil eden bayt dizisi. |
| password | const [String](../../../system/string/)\& | Sertifika verilerine erişmek için kullanılan şifre. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodlanmış sertifikayı temsil eden bayt dizisi. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Sertifika verilerine erişmek için kullanılan şifre. |

## X509Certificate::X509Certificate(const String\&, const String\&) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Sertifikanın yükleneceği dosya. |
| password | const [String](../../../system/string/)\& | Sertifika verilerine erişmek için kullanılan şifre. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Sertifikanın yükleneceği dosya. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Sertifika verilerine erişmek için kullanılan şifre. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodlanmış sertifikayı temsil eden bayt dizisi. |
| password | const [String](../../../system/string/)\& | Sertifika verilerine erişmek için kullanılan şifre. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Anahtarı nasıl saklayacağını belirten bayraklar. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodlanmış sertifikayı temsil eden bayt dizisi. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Sertifika verilerine erişmek için kullanılan şifre. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Anahtarı nasıl saklayacağını belirten bayraklar. |

## X509Certificate::X509Certificate(const String\&, const String\&, X509KeyStorageFlags) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Sertifikanın yükleneceği dosya. |
| password | const [String](../../../system/string/)\& | Sertifika verilerine erişmek için kullanılan şifre. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Anahtarı nasıl saklayacağını belirten bayraklar. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Sertifikanın yükleneceği dosya. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Sertifika verilerine erişmek için kullanılan şifre. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Anahtarı nasıl saklayacağını belirten bayraklar. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodlanmış sertifikayı (genel bölüm) temsil eden bayt dizisi. |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Özel anahtarı temsil eden bayt dizisi. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Anahtarı nasıl saklayacağını belirten bayraklar. |

## İlgili

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Sınıf [X509Certificate](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [System::Security::Cryptography::X509Certificates](../../)
* Kütüphane [Aspose.Slides](../../../)