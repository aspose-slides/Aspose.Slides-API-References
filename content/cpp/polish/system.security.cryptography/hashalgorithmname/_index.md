---
title: HashAlgorithmName
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Ciąg znaków reprezentujący nazwę algorytmu skrótu. Ten typ powinien być przydzielany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 755
url: /pl/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName struct


[String](../../system/string/) reprezentująca nazwę algorytmu skrótu. Ten typ powinien być przydzielany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy [System::SmartPtr](../../system/smartptr/) do zarządzania obiektami tego typu.

```cpp
class HashAlgorithmName
```

## Metody

| Metoda | Opis |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | Utwórz [HashAlgorithmName](./) z wartości OID. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | Zwraca [HashAlgorithmName](./) reprezentujący [MD5](../md5/). |
| [String](../../system/string/) [get_Name](./get_name/)() const | Zwraca ciąg znaków reprezentujący nazwę algorytmu. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | Zwraca [HashAlgorithmName](./) reprezentujący [SHA1](../sha1/). |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | Zwraca [HashAlgorithmName](./) reprezentujący [SHA256](../sha256/). |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | Zwraca [HashAlgorithmName](./) reprezentujący [SHA384](../sha384/). |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | Zwraca [HashAlgorithmName](./) reprezentujący [SHA512](../sha512/). |
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
| [String](../../system/string/) [ToString](./tostring/)() const | Zwraca ciąg znaków reprezentujący nazwę algorytmu. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | Spróbuj utworzyć [HashAlgorithmName](./) z wartości OID. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | Zwraca obiekt [TypeInfo](../../system/typeinfo/), który reprezentuje strukturę [TimeSpan](../../system/timespan/). |
## Zobacz także

* Przestrzeń nazw [System::Security::Cryptography](../)
* Biblioteka [Aspose.Slides](../../)