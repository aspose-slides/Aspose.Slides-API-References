---
title: X509Certificate2()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een lege X509Certificate2.
type: docs
weight: 1
url: /nl/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() constructor

Construeert een lege [X509Certificate2](../).

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Bestand om certificaat van te laden. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | Een [X509Certificate](../../x509certificate/) object. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Reeks bytes die het gecodeerde certificaat vertegenwoordigt. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Reeks bytes die het gecodeerde certificaat vertegenwoordigt. |
| password | const [String](../../../system/string/)\& | Certificaatwachtwoord. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Reeks bytes die het gecodeerde certificaat vertegenwoordigt. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Certificaatwachtwoord. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Reeks bytes die het gecodeerde certificaat vertegenwoordigt. |
| password | const [String](../../../system/string/)\& | Certificaatwachtwoord. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Vlaggen die aangeven hoe de sleutel moet worden opgeslagen. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Reeks bytes die het gecodeerde certificaat vertegenwoordigt. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Certificaatwachtwoord. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Vlaggen die aangeven hoe de sleutel moet worden opgeslagen. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Bestand om certificaat van te laden. |
| password | const [String](../../../system/string/)\& | Certificaatwachtwoord. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Bestand om certificaat van te laden. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Certificaatwachtwoord. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Bestand om certificaat van te laden. |
| password | const [String](../../../system/string/)\& | Certificaatwachtwoord. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Vlaggen die aangeven hoe de sleutel moet worden opgeslagen. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Bestand om certificaat van te laden. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Certificaatwachtwoord. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Vlaggen die aangeven hoe de sleutel moet worden opgeslagen. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Reeks bytes die het gecodeerde certificaat (publiek deel) vertegenwoordigt. |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Reeks bytes die de privésleutel vertegenwoordigt. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Vlaggen die aangeven hoe de sleutel moet worden opgeslagen. |

## Zie ook

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)