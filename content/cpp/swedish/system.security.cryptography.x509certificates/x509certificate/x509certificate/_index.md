---
title: X509Certificate()
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 1
url: /sv/system.security.cryptography.x509certificates/x509certificate/x509certificate/
---
## X509Certificate::X509Certificate(const X509Certificate\&) konstruktor




```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const X509Certificate &)=delete
```

## X509Certificate::X509Certificate() konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate()
```

## X509Certificate::X509Certificate(const ByteArrayPtr\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &data)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvens av byte som representerar kodad certifikat. |

## X509Certificate::X509Certificate(const String\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Fil att läsa certifikat från. |

## X509Certificate::X509Certificate(const SharedPtr\<X509Certificate\>\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const SharedPtr<X509Certificate> &cert)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../)\>\& | Ett certifikat som används för att initiera detta objekt. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvens av byte som representerar kodad certifikat. |
| password | const [String](../../../system/string/)\& | Lösenord som används för att komma åt certifikatdata. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvens av byte som representerar kodad certifikat. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Lösenord som används för att komma åt certifikatdata. |

## X509Certificate::X509Certificate(const String\&, const String\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Fil att läsa certifikat från. |
| password | const [String](../../../system/string/)\& | Lösenord som används för att komma åt certifikatdata. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Fil att läsa certifikat från. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Lösenord som används för att komma åt certifikatdata. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvens av byte som representerar kodad certifikat. |
| password | const [String](../../../system/string/)\& | Lösenord som används för att komma åt certifikatdata. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flaggor som anger hur nyckeln ska lagras. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvens av byte som representerar kodad certifikat. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Lösenord som används för att komma åt certifikatdata. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flaggor som anger hur nyckeln ska lagras. |

## X509Certificate::X509Certificate(const String\&, const String\&, X509KeyStorageFlags) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Fil att läsa certifikat från. |
| password | const [String](../../../system/string/)\& | Lösenord som används för att komma åt certifikatdata. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flaggor som anger hur nyckeln ska lagras. |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Fil att läsa certifikat från. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Lösenord som används för att komma åt certifikatdata. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flaggor som anger hur nyckeln ska lagras. |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvens av byte som representerar kodad certifikat (publik del). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvens av byte som representerar privat nyckel. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flaggor som anger hur nyckeln ska lagras. |

## Se även

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Klass [X509Certificate](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Security::Cryptography::X509Certificates](../../)
* Bibliotek [Aspose.Slides](../../../)