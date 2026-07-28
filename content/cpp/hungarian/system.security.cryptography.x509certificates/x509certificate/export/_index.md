---
title: Export()
second_title: Aspose.Slides C++ API Referenciája
description: Az aktuális objektumot egy bájttömbbe exportálja a megadott formátummal. NEM VALÓSÍTOTT.
type: docs
weight: 287
url: /hu/system.security.cryptography.x509certificates/x509certificate/export/
---
## X509Certificate::Export(X509ContentType) const metódus


Az aktuális objektumot egy bájttömbbe exportálja a megadott formátummal. NEM VALÓSÍTOTT.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | Megadja, hogyan kell formázni a kimeneti adatokat. |

### Visszatérési érték

Egy bájttömb, amely az aktuális objektumot reprezentálja.

## X509Certificate::Export(X509ContentType, const SecureStringPtr\&) const metódus


Az aktuális objektumot egy bájttömbbe exportálja a megadott formátummal. NEM VALÓSÍTOTT.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const SecureStringPtr &password) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | Megadja, hogyan kell formázni a kimeneti adatokat. |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | A jelszó, amely a tanúsítvány adatainak eléréséhez szükséges. |

### Visszatérési érték

Egy bájttömb, amely az aktuális objektumot reprezentálja.

## X509Certificate::Export(X509ContentType, const String\&) const metódus


Az aktuális objektumot egy bájttömbbe exportálja a megadott formátummal. NEM VALÓSÍTOTT.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const String &password) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | Megadja, hogyan kell formázni a kimeneti adatokat. |
| password | const [String](../../../system/string/)\& | A jelszó, amely a tanúsítvány adatainak eléréséhez szükséges. |

### Visszatérési érték

Egy bájttömb, amely az aktuális objektumot reprezentálja.

## Lásd még

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Osztály [X509Certificate](../)
* Osztály [String](../../../system/string/)
* Névterület [System::Security::Cryptography::X509Certificates](../../)
* Könyvtár [Aspose.Slides](../../../)