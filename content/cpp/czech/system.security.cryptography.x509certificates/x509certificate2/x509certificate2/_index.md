---
title: X509Certificate2()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří prázdný X509Certificate2.
type: docs
weight: 1
url: /cs/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() konstruktor


Vytvoří prázdný [X509Certificate2](../).

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Soubor, ze kterého se načte certifikát. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | Objekt [X509Certificate](../../x509certificate/). |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvence bytů představující kódovaný certifikát. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvence bytů představující kódovaný certifikát. |
| password | const [String](../../../system/string/)\& | Heslo certifikátu. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvence bytů představující kódovaný certifikát. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Heslo certifikátu. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvence bytů představující kódovaný certifikát. |
| password | const [String](../../../system/string/)\& | Heslo certifikátu. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Příznaky určující, jak uložit klíč. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvence bytů představující kódovaný certifikát. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Heslo certifikátu. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Příznaky určující, jak uložit klíč. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Soubor, ze kterého se načte certifikát. |
| password | const [String](../../../system/string/)\& | Heslo certifikátu. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Soubor, ze kterého se načte certifikát. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Heslo certifikátu. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Soubor, ze kterého se načte certifikát. |
| password | const [String](../../../system/string/)\& | Heslo certifikátu. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Příznaky určující, jak uložit klíč. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Soubor, ze kterého se načte certifikát. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Heslo certifikátu. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Příznaky určující, jak uložit klíč. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvence bytů představující kódovaný certifikát (veřejná část). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvence bytů představující soukromý klíč. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Příznaky určující, jak uložit klíč. |

## Viz také

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)