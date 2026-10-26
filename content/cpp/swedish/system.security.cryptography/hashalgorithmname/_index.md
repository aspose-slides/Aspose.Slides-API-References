---
title: HashAlgorithmName
second_title: Aspose.Slides för C++ API-referens
description: "Sträng som representerar namnet på en hash-algoritm. Denna typ bör allokeras på stacken och skickas till funktioner efter värde eller referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ."
type: docs
weight: 755
url: /sv/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName struct

[String](../../system/string/) som representerar namnet på en hash-algoritm. Denna typ bör allokeras på stacken och skickas till funktioner efter värde eller referens. Använd aldrig [System::SmartPtr](../../system/smartptr/) klass för att hantera objekt av denna typ.

```cpp
class HashAlgorithmName
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | Skapa [HashAlgorithmName](./) från OID-värde. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | Hämtar en [HashAlgorithmName](./) som representerar [MD5](../md5/). |
| [String](../../system/string/) [get_Name](./get_name/)() const | Hämtar strängrepresentation av algoritmens namn. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | Hämtar en [HashAlgorithmName](./) som representerar [SHA1](../sha1/). |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | Hämtar en [HashAlgorithmName](./) som representerar [SHA256](../sha256/). |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | Hämtar en [HashAlgorithmName](./) som representerar [SHA384](../sha384/). |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | Hämtar en [HashAlgorithmName](./) som representerar [SHA512](../sha512/). |
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
| [String](../../system/string/) [ToString](./tostring/)() const | Hämtar strängrepresentation av algoritmens namn. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | Försök att skapa [HashAlgorithmName](./) från OID-värde. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | Returnerar ett [TypeInfo](../../system/typeinfo/)-objekt som representerar [TimeSpan](../../system/timespan/)-strukturen. |

## Se även

* Namnrymd [System::Security::Cryptography](../)
* Bibliotek [Aspose.Slides](../../)