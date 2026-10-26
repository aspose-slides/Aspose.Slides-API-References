---
title: X509Certificate2()
second_title: Aspose.Slides for C++ API-referencia
description: Üres X509Certificate2 objektumot hoz létre.
type: docs
weight: 1
url: /hu/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() konstruktor

Üres [X509Certificate2](../) objektumot hoz létre.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A tanúsítvány betöltéséhez használandó fájl. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | Egy [X509Certificate](../../x509certificate/) objektum. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A kódolt tanúsítványt ábrázoló bájtok sorozata. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A kódolt tanúsítványt ábrázoló bájtok sorozata. |
| password | const [String](../../../system/string/)\& | A tanúsítvány jelszava. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A kódolt tanúsítványt ábrázoló bájtok sorozata. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | A tanúsítvány jelszava. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A kódolt tanúsítványt ábrázoló bájtok sorozata. |
| password | const [String](../../../system/string/)\& | A tanúsítvány jelszava. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | A kulcs tárolásának módját jelző jelzők. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A kódolt tanúsítványt ábrázoló bájtok sorozata. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | A tanúsítvány jelszava. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | A kulcs tárolásának módját jelző jelzők. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A tanúsítvány betöltéséhez használandó fájl. |
| password | const [String](../../../system/string/)\& | A tanúsítvány jelszava. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A tanúsítvány betöltéséhez használandó fájl. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | A tanúsítvány jelszava. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A tanúsítvány betöltéséhez használandó fájl. |
| password | const [String](../../../system/string/)\& | A tanúsítvány jelszava. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | A kulcs tárolásának módját jelző jelzők. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A tanúsítvány betöltéséhez használandó fájl. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | A tanúsítvány jelszava. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | A kulcs tárolásának módját jelző jelzők. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A kódolt tanúsítványt (nyilvános rész) ábrázoló bájtok sorozata. |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A privát kulcsot ábrázoló bájtok sorozata. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | A kulcs tárolásának módját jelző jelzők. |

## Lásd még

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)