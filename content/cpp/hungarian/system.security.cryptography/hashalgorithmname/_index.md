---
title: HashAlgorithmName
second_title: Aspose.Slides for C++ API referencia
description: "Karakterlánc, amely egy hash algoritmus nevét reprezentálja. Ezt a típust a stacken kell lefoglalni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 755
url: /hu/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName struktúra


[String](../../system/string/) a hash algoritmus nevének reprezentálására. Ez a típus a stacken kell, hogy legyen lefoglalva és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../../system/smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
class HashAlgorithmName
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | Létrehozza a [HashAlgorithmName](./)-t OID-értékből. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | Kap egy [HashAlgorithmName](./)-t, amely [MD5](../md5/)-t reprezentál. |
| [String](../../system/string/) [get_Name](./get_name/)() const | A algoritmus nevének karakterlánc reprezentációját adja vissza. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | Kap egy [HashAlgorithmName](./)-t, amely [SHA1](../sha1/)-t reprezentál. |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | Kap egy [HashAlgorithmName](./)-t, amely [SHA256](../sha256/)-t reprezentál. |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | Kap egy [HashAlgorithmName](./)-t, amely [SHA384](../sha384/)-t reprezentál. |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | Kap egy [HashAlgorithmName](./)-t, amely [SHA512](../sha512/)-t reprezentál. |
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
| [String](../../system/string/) [ToString](./tostring/)() const | A algoritmus nevének karakterlánc reprezentációját adja vissza. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | Megpróbálja létrehozni a [HashAlgorithmName](./)-t OID-értékből. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | Visszaad egy [TypeInfo](../../system/typeinfo/) objektumot, amely a [TimeSpan](../../system/timespan/) struktúrát reprezentálja. |
## Lásd még

* Névtér [System::Security::Cryptography](../)
* Könyvtár [Aspose.Slides](../../)