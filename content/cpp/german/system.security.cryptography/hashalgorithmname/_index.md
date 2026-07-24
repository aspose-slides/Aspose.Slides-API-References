---
title: HashAlgorithmName
second_title: Aspose.Slides für C++ API-Referenz
description: "String, der den Namen eines Hash-Algorithmus repräsentiert. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die System::SmartPtr-Klasse, um Objekte dieses Typs zu verwalten."
type: docs
weight: 755
url: /de/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName Struktur


[String](../../system/string/) repräsentiert den Namen eines Hash-Algorithmus. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../../system/smartptr/) Klasse, um Objekte dieses Typs zu verwalten.

```cpp
class HashAlgorithmName
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | Erstelle [HashAlgorithmName](./) aus OID-Wert. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | Gibt ein [HashAlgorithmName](./) zurück, das [MD5](../md5/) darstellt. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Gibt die String-Darstellung des Algorithmusnamens zurück. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | Gibt ein [HashAlgorithmName](./) zurück, das [SHA1](../sha1/) darstellt. |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | Gibt ein [HashAlgorithmName](./) zurück, das [SHA256](../sha256/) darstellt. |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | Gibt ein [HashAlgorithmName](./) zurück, das [SHA384](../sha384/) darstellt. |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | Gibt ein [HashAlgorithmName](./) zurück, das [SHA512](../sha512/) darstellt. |
| int [GetHashCode](./gethashcode/)() const |  |
|  [HashAlgorithmName](./hashalgorithmname/)() |  |
|  [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | Konstruktor. |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [HashAlgorithmName](./)\&) const |  |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [HashAlgorithmName](./)\& [operator=](./operator_equal/)(const [HashAlgorithmName](./)\&) |  |
| **bool** [operator==](./operator_equal_equal/)(const [HashAlgorithmName](./)\&) const |  |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| [String](../../system/string/) [ToString](./tostring/)() const | Gibt die String-Darstellung des Algorithmusnamens zurück. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | Versucht, [HashAlgorithmName](./) aus OID-Wert zu erstellen. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | Gibt ein [TypeInfo](../../system/typeinfo/)-Objekt zurück, das die [TimeSpan](../../system/timespan/)-Struktur repräsentiert. |

## Siehe auch

* Namensraum [System::Security::Cryptography](../)
* Bibliothek [Aspose.Slides](../../)