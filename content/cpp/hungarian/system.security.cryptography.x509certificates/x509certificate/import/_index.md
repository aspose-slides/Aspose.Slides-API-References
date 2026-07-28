---
title: Import()
second_title: Aspose.Slides C++ API referencia
description: Importálja az információkat a megadott tanúsítványfájlból. NEM VALÓSÍTOTT MEG.
type: docs
weight: 300
url: /hu/system.security.cryptography.x509certificates/x509certificate/import/
---
## X509Certificate::Import(const String&, const SecureStringPtr&, X509KeyStorageFlags) metódus


Importálja az információkat a megadott tanúsítványfájlból. NEM VALÓSÍTOTT MEG.

```cpp
virtual void System::Security::Cryptography::X509Certificates::X509Certificate::Import(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A tanúsítványfájl neve. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | A tanúsítványadatok eléréséhez szükséges jelszó. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate::Import(const String&, const String&, X509KeyStorageFlags) metódus


Importálja az információkat a megadott tanúsítványfájlból. NEM VALÓSÍTOTT MEG.

```cpp
virtual void System::Security::Cryptography::X509Certificates::X509Certificate::Import(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A tanúsítványfájl neve. |
| password | const [String](../../../system/string/)\& | A tanúsítványadatok eléréséhez szükséges jelszó. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate::Import(const ByteArrayPtr&, const SecureStringPtr&, X509KeyStorageFlags) metódus


Importálja az információkat a megadott tanúsítványadatokból. NEM VALÓSÍTOTT MEG.

```cpp
virtual void System::Security::Cryptography::X509Certificates::X509Certificate::Import(const ByteArrayPtr &data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Az X.509 tanúsítvány adatai. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | A tanúsítványadatok eléréséhez szükséges jelszó. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate::Import(const ByteArrayPtr&, const String&, X509KeyStorageFlags) metódus


Importálja az információkat a megadott tanúsítványadatokból. NEM VALÓSÍTOTT MEG.

```cpp
virtual void System::Security::Cryptography::X509Certificates::X509Certificate::Import(const ByteArrayPtr &data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A tanúsítványfájl neve. |
| password | const [String](../../../system/string/)\& | A tanúsítványadatok eléréséhez szükséges jelszó. |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) |  |

## X509Certificate::Import(const String&) metódus


Importálja az információkat a megadott tanúsítványfájlból. NEM VALÓSÍTOTT MEG.

```cpp
virtual void System::Security::Cryptography::X509Certificates::X509Certificate::Import(const String &filename)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A tanúsítványfájl neve. |

## X509Certificate::Import(const ByteArrayPtr&) metódus


Importálja az információkat a megadott tanúsítványadatokból. NEM VALÓSÍTOTT MEG.

```cpp
virtual void System::Security::Cryptography::X509Certificates::X509Certificate::Import(const ByteArrayPtr &data)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A tanúsítványfájl neve. |

## Lásd még

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [X509Certificate](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)