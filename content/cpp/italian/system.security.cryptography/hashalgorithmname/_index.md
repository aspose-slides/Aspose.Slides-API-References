---
title: HashAlgorithmName
second_title: Riferimento API di Aspose.Slides per C++
description: "Stringa che rappresenta il nome di un algoritmo hash. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 755
url: /it/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName struct

[String](../../system/string/) che rappresenta il nome di un algoritmo hash. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe [System::SmartPtr](../../system/smartptr/) per gestire oggetti di questo tipo.

```cpp
class HashAlgorithmName
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | Crea [HashAlgorithmName](./) dal valore OID. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | Ottiene un [HashAlgorithmName](./) che rappresenta [MD5](../md5/). |
| [String](../../system/string/) [get_Name](./get_name/)() const | Ottiene la rappresentazione stringa del nome dell'algoritmo. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | Ottiene un [HashAlgorithmName](./) che rappresenta [SHA1](../sha1/). |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | Ottiene un [HashAlgorithmName](./) che rappresenta [SHA256](../sha256/). |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | Ottiene un [HashAlgorithmName](./) che rappresenta [SHA384](../sha384/). |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | Ottiene un [HashAlgorithmName](./) che rappresenta [SHA512](../sha512/). |
| int [GetHashCode](./gethashcode/)() const |  |
|  [HashAlgorithmName](./hashalgorithmname/)() |  |
|  [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | Costruttore. |
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
| [String](../../system/string/) [ToString](./tostring/)() const | Ottiene la rappresentazione stringa del nome dell'algoritmo. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | Prova a creare [HashAlgorithmName](./) dal valore OID. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | Restituisce un oggetto [TypeInfo](../../system/typeinfo/) che rappresenta la struttura [TimeSpan](../../system/timespan/). |

## Vedi anche

* Spazio dei nomi [System::Security::Cryptography](../)
* Libreria [Aspose.Slides](../../)