---
title: HashAlgorithmName
second_title: Aspose.Slides voor C++ API-referentie
description: "String die de naam van een hash-algoritme vertegenwoordigt. Dit type moet op de stack worden gealloceerd en aan functies per waarde of per referentie worden doorgegeven. Gebruik nooit de System::SmartPtr class om objecten van dit type te beheren."
type: docs
weight: 755
url: /nl/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName struct


[String](../../system/string/) die de naam van een hash-algoritme vertegenwoordigt. Dit type moet op de stack worden gealloceerd en aan functies doorgegeven worden per waarde of per referentie. Gebruik nooit de [System::SmartPtr](../../system/smartptr/) class om objecten van dit type te beheren.

```cpp
class HashAlgorithmName
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | Maak [HashAlgorithmName](./) aan vanuit een OID-waarde. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | Verkrijgt een [HashAlgorithmName](./) die [MD5](../md5/) vertegenwoordigt. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Verkrijgt de stringrepresentatie van de algoritme-naam. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | Verkrijgt een [HashAlgorithmName](./) die [SHA1](../sha1/) vertegenwoordigt. |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | Verkrijgt een [HashAlgorithmName](./) die [SHA256](../sha256/) vertegenwoordigt. |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | Verkrijgt een [HashAlgorithmName](./) die [SHA384](../sha384/) vertegenwoordigt. |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | Verkrijgt een [HashAlgorithmName](./) die [SHA512](../sha512/) vertegenwoordigt. |
| int [GetHashCode](./gethashcode/)() const |  |
|  [HashAlgorithmName](./hashalgorithmname/)() |  |
|  [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | Constructor. |
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
| [String](../../system/string/) [ToString](./tostring/)() const | Verkrijgt de stringrepresentatie van de algoritme-naam. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | Probeer [HashAlgorithmName](./) te maken vanuit een OID-waarde. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | Retourneert een [TypeInfo](../../system/typeinfo/) object dat de [TimeSpan](../../system/timespan/) structuur vertegenwoordigt. |
## Zie ook

* Naamruimte [System::Security::Cryptography](../)
* Library [Aspose.Slides](../../)