---
title: HashAlgorithmName
second_title: Référence de l'API Aspose.Slides pour C++
description: "Chaîne représentant le nom d'un algorithme de hachage. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer les objets de ce type."
type: docs
weight: 755
url: /fr/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName structure

[String](../../system/string/) représentant le nom d'un algorithme de hachage. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe [System::SmartPtr](../../system/smartptr/) pour gérer les objets de ce type.

```cpp
class HashAlgorithmName
```

## Methods

| Méthode | Description |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | Créer [HashAlgorithmName](./) à partir d'une valeur OID. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | Obtient un [HashAlgorithmName](./) représentant [MD5](../md5/). |
| [String](../../system/string/) [get_Name](./get_name/)() const | Obtient la représentation sous forme de chaîne du nom de l'algorithme. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | Obtient un [HashAlgorithmName](./) représentant [SHA1](../sha1/). |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | Obtient un [HashAlgorithmName](./) représentant [SHA256](../sha256/). |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | Obtient un [HashAlgorithmName](./) représentant [SHA384](../sha384/). |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | Obtient un [HashAlgorithmName](./) représentant [SHA512](../sha512/). |
| int [GetHashCode](./gethashcode/)() const |  |
| [HashAlgorithmName](./hashalgorithmname/)() |  |
| [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | Constructeur. |
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
| [String](../../system/string/) [ToString](./tostring/)() const | Obtient la représentation sous forme de chaîne du nom de l'algorithme. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | Essayer de créer [HashAlgorithmName](./) à partir d'une valeur OID. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | Renvoie un objet [TypeInfo](../../system/typeinfo/) qui représente la structure [TimeSpan](../../system/timespan/). |

## Voir aussi

* Espace de noms [System::Security::Cryptography](../)
* Bibliothèque [Aspose.Slides](../../)