---
title: X509Certificate2()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt ein leeres X509Certificate2.
type: docs
weight: 1
url: /de/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() Konstruktor

Erstellt ein leeres [X509Certificate2](../).

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) Konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Datei, aus der das Zertifikat geladen wird. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) Konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | Ein [X509Certificate](../../x509certificate/) Objekt. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) Konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenz von Bytes, die das kodierte Zertifikat darstellen. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) Konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenz von Bytes, die das kodierte Zertifikat darstellen. |
| password | const [String](../../../system/string/)\& | Zertifikatspasswort. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) Konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenz von Bytes, die das kodierte Zertifikat darstellen. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Zertifikatspasswort. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) Konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenz von Bytes, die das kodierte Zertifikat darstellen. |
| password | const [String](../../../system/string/)\& | Zertifikatspasswort. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags, die angeben, wie der Schlüssel gespeichert wird. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) Konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenz von Bytes, die das kodierte Zertifikat darstellen. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Zertifikatspasswort. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags, die angeben, wie der Schlüssel gespeichert wird. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) Konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Datei, aus der das Zertifikat geladen wird. |
| password | const [String](../../../system/string/)\& | Zertifikatspasswort. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) Konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Datei, aus der das Zertifikat geladen wird. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Zertifikatspasswort. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) Konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Datei, aus der das Zertifikat geladen wird. |
| password | const [String](../../../system/string/)\& | Zertifikatspasswort. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags, die angeben, wie der Schlüssel gespeichert wird. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) Konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Datei, aus der das Zertifikat geladen wird. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Zertifikatspasswort. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags, die angeben, wie der Schlüssel gespeichert wird. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) Konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenz von Bytes, die das kodierte Zertifikat (öffentlicher Teil) darstellen. |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sequenz von Bytes, die den privaten Schlüssel darstellen. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flags, die angeben, wie der Schlüssel gespeichert wird. |

## Siehe Auch

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Klasse [X509Certificate2](../)
* Klasse [String](../../../system/string/)
* Klasse [X509Certificate](../../x509certificate/)
* Namensraum [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)