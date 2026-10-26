---
title: X509Certificate2()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en tom X509Certificate2.
type: docs
weight: 1
url: /sv/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() konstruktor

Skapar tom [X509Certificate2](../).

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Fil att läsa certifikat från. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | Ett [X509Certificate](../../x509certificate/)-objekt. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvens av byte som representerar kodad certifikat. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvens av byte som representerar kodad certifikat. |
| password | const [String](../../../system/string/)\& | Certifikatlösenord. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvens av byte som representerar kodad certifikat. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Certifikatlösenord. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvens av byte som representerar kodad certifikat. |
| password | const [String](../../../system/string/)\& | Certifikatlösenord. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flaggor som indikerar hur nyckeln ska lagras. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvens av byte som representerar kodad certifikat. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Certifikatlösenord. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flaggor som indikerar hur nyckeln ska lagras. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Fil att läsa certifikat från. |
| password | const [String](../../../system/string/)\& | Certifikatlösenord. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Fil att läsa certifikat från. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Certifikatlösenord. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Fil att läsa certifikat från. |
| password | const [String](../../../system/string/)\& | Certifikatlösenord. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flaggor som indikerar hur nyckeln ska lagras. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Fil att läsa certifikat från. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Certifikatlösenord. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flaggor som indikerar hur nyckeln ska lagras. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvens av byte som representerar kodad certifikat (offentlig del). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekvens av byte som representerar privat nyckel. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flaggor som indikerar hur nyckeln ska lagras. |

## Se även

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Klass [X509Certificate2](../)
* Klass [String](../../../system/string/)
* Klass [X509Certificate](../../x509certificate/)
* Namnrymd [System::Security::Cryptography::X509Certificates](../../)
* Bibliotek [Aspose.Slides](../../../)