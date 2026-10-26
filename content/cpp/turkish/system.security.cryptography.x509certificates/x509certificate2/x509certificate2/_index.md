---
title: X509Certificate2()
second_title: Aspose.Slides için C++ API Referansı
description: Boş X509Certificate2 oluşturur.
type: docs
weight: 1
url: /tr/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() yapıcı


Boş [X509Certificate2](../) oluşturur.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Sertifikanın yükleneceği dosya. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | Bir [X509Certificate](../../x509certificate/) nesnesi. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodlanmış sertifikayı temsil eden bayt dizisi. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodlanmış sertifikayı temsil eden bayt dizisi. |
| password | const [String](../../../system/string/)\& | Sertifika parolası. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodlanmış sertifikayı temsil eden bayt dizisi. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Sertifika parolası. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodlanmış sertifikayı temsil eden bayt dizisi. |
| password | const [String](../../../system/string/)\& | Sertifika parolası. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Anahtarın nasıl depolanacağını belirten bayraklar. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodlanmış sertifikayı temsil eden bayt dizisi. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Sertifika parolası. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Anahtarın nasıl depolanacağını belirten bayraklar. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Sertifikanın yükleneceği dosya. |
| password | const [String](../../../system/string/)\& | Sertifika parolası. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Sertifikanın yükleneceği dosya. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Sertifika parolası. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Sertifikanın yükleneceği dosya. |
| password | const [String](../../../system/string/)\& | Sertifika parolası. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Anahtarın nasıl depolanacağını belirten bayraklar. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Sertifikanın yükleneceği dosya. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Sertifika parolası. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Anahtarın nasıl depolanacağını belirten bayraklar. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) yapıcı


Yapıcı.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodlanmış sertifikayı (genel kısmı) temsil eden bayt dizisi. |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Özel anahtarı temsil eden bayt dizisi. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Anahtarın nasıl depolanacağını belirten bayraklar. |

## Diğer Bilgiler

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)