---
title: HashAlgorithmName
second_title: Aspose.Slides pro C++ - reference API
description: "Řetězec představující název hashovacího algoritmu. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu System::SmartPtr k řízení objektů tohoto typu."
type: docs
weight: 755
url: /cs/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName struct

[String](../../system/string/) představující název hashovacího algoritmu. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](../../system/smartptr/) k řízení objektů tohoto typu.

```cpp
class HashAlgorithmName
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | Vytvořit [HashAlgorithmName](./) z OID-hodnoty. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | Získá [HashAlgorithmName](./) představující [MD5](../md5/). |
| [String](../../system/string/) [get_Name](./get_name/)() const | Získá řetězcovou reprezentaci názvu algoritmu. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | Získá [HashAlgorithmName](./) představující [SHA1](../sha1/). |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | Získá [HashAlgorithmName](./) představující [SHA256](../sha256/). |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | Získá [HashAlgorithmName](./) představující [SHA384](../sha384/). |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | Získá [HashAlgorithmName](./) představující [SHA512](../sha512/). |
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
| [String](../../system/string/) [ToString](./tostring/)() const | Získá řetězcovou reprezentaci názvu algoritmu. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | Zkusit vytvořit [HashAlgorithmName](./) z OID-hodnoty. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | Vrátí objekt [TypeInfo](../../system/typeinfo/) který reprezentuje strukturu [TimeSpan](../../system/timespan/). |

## Viz také

* jmenný prostor [System::Security::Cryptography](../)
* Knihovna [Aspose.Slides](../../)