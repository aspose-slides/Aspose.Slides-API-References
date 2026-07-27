---
title: HashAlgorithmName
second_title: Referência da API Aspose.Slides para C++
description: "String que representa o nome de um algoritmo de hash. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos deste tipo."
type: docs
weight: 755
url: /pt/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName struct

[String](../../system/string/) representando o nome de um algoritmo de hash. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../../system/smartptr/) para gerenciar objetos deste tipo.

```cpp
class HashAlgorithmName
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | Cria [HashAlgorithmName](./) a partir do valor OID. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | Obtém um [HashAlgorithmName](./) que representa [MD5](../md5/). |
| [String](../../system/string/) [get_Name](./get_name/)() const | Obtém a representação em string do nome do algoritmo. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | Obtém um [HashAlgorithmName](./) que representa [SHA1](../sha1/). |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | Obtém um [HashAlgorithmName](./) que representa [SHA256](../sha256/). |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | Obtém um [HashAlgorithmName](./) que representa [SHA384](../sha384/). |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | Obtém um [HashAlgorithmName](./) que representa [SHA512](../sha512/). |
| int [GetHashCode](./gethashcode/)() const |  |
|  [HashAlgorithmName](./hashalgorithmname/)() |  |
|  [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | Construtor. |
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
| [String](../../system/string/) [ToString](./tostring/)() const | Obtém a representação em string do nome do algoritmo. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | Tente criar [HashAlgorithmName](./) a partir do valor OID. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | Retorna um objeto [TypeInfo](../../system/typeinfo/) que representa a estrutura [TimeSpan](../../system/timespan/). |

## Veja Também

* Namespace [System::Security::Cryptography](../)
* Biblioteca [Aspose.Slides](../../)