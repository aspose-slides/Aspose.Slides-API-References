---
title: HashAlgorithmName
second_title: Aspose.Slides para C++ Referencia de la API
description: "Cadena que representa el nombre de un algoritmo de hash. Este tipo debe asignarse en la pila y pasarse a las funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 755
url: /es/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName struct

[String](../../system/string/) que representa el nombre de un algoritmo de hash. Este tipo debe ser asignado en la pila y pasado a las funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../../system/smartptr/) para gestionar objetos de este tipo.

```cpp
class HashAlgorithmName
```

## Métodos

| Método | Descripción |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | Crear [HashAlgorithmName](./) a partir del valor OID. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | Obtiene un [HashAlgorithmName](./) que representa [MD5](../md5/). |
| [String](../../system/string/) [get_Name](./get_name/)() const | Obtiene la representación en cadena del nombre del algoritmo. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | Obtiene un [HashAlgorithmName](./) que representa [SHA1](../sha1/). |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | Obtiene un [HashAlgorithmName](./) que representa [SHA256](../sha256/). |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | Obtiene un [HashAlgorithmName](./) que representa [SHA384](../sha384/). |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | Obtiene un [HashAlgorithmName](./) que representa [SHA512](../sha512/). |
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
| [String](../../system/string/) [ToString](./tostring/)() const | Obtiene la representación en cadena del nombre del algoritmo. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | Intenta crear [HashAlgorithmName](./) a partir del valor OID. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | Devuelve un objeto [TypeInfo](../../system/typeinfo/) que representa la estructura [TimeSpan](../../system/timespan/). |

## Ver también

* Espacio de nombres [System::Security::Cryptography](../)
* Biblioteca [Aspose.Slides](../../)