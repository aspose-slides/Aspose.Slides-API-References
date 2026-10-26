---
title: X509Certificate2()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy pusty X509Certificate2.
type: docs
weight: 1
url: /pl/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() konstruktor


Tworzy pusty [X509Certificate2](../).

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Plik do wczytania certyfikatu. |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | Obiekt [X509Certificate](../../x509certificate/). |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekwencja bajtów reprezentująca zakodowany certyfikat. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekwencja bajtów reprezentująca zakodowany certyfikat. |
| password | const [String](../../../system/string/)\& | Hasło certyfikatu. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekwencja bajtów reprezentująca zakodowany certyfikat. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Hasło certyfikatu. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekwencja bajtów reprezentująca zakodowany certyfikat. |
| password | const [String](../../../system/string/)\& | Hasło certyfikatu. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flagi określające sposób przechowywania klucza. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekwencja bajtów reprezentująca zakodowany certyfikat. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Hasło certyfikatu. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flagi określające sposób przechowywania klucza. |

## X509Certificate2::X509Certificate2(const String\&, const String\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Plik do wczytania certyfikatu. |
| password | const [String](../../../system/string/)\& | Hasło certyfikatu. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Plik do wczytania certyfikatu. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Hasło certyfikatu. |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Plik do wczytania certyfikatu. |
| password | const [String](../../../system/string/)\& | Hasło certyfikatu. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flagi określające sposób przechowywania klucza. |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Plik do wczytania certyfikatu. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | Hasło certyfikatu. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flagi określające sposób przechowywania klucza. |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekwencja bajtów reprezentująca zakodowany certyfikat (część publiczna). |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Sekwencja bajtów reprezentująca klucz prywatny. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | Flagi określające sposób przechowywania klucza. |

## Zobacz także

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)