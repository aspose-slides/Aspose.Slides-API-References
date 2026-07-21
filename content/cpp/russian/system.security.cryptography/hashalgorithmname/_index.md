---
title: HashAlgorithmName
second_title: Aspose.Slides для C++ API справка
description: "Строка, представляющая имя хэш-алгоритма. Этот тип следует выделять в стеке и передавать функциям по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа."
type: docs
weight: 755
url: /ru/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName struct

[String](../../system/string/) представляет имя хэш-алгоритма. Этот тип следует создавать в стеке и передавать функциям по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../../system/smartptr/) для управления объектами этого типа.

```cpp
class HashAlgorithmName
```

## Методы

| Метод | Описание |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | Создать [HashAlgorithmName](./) из значения OID. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | Получает [HashAlgorithmName](./), представляющий [MD5](../md5/). |
| [String](../../system/string/) [get_Name](./get_name/)() const | Получает строковое представление имени алгоритма. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | Получает [HashAlgorithmName](./), представляющий [SHA1](../sha1/). |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | Получает [HashAlgorithmName](./), представляющий [SHA256](../sha256/). |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | Получает [HashAlgorithmName](./), представляющий [SHA384](../sha384/). |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | Получает [HashAlgorithmName](./), представляющий [SHA512](../sha512/). |
| int [GetHashCode](./gethashcode/)() const |  |
| [HashAlgorithmName](./hashalgorithmname/)() |  |
| [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | Конструктор. |
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
| [String](../../system/string/) [ToString](./tostring/)() const | Получает строковое представление имени алгоритма. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | Попробовать создать [HashAlgorithmName](./) из значения OID. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | Возвращает объект [TypeInfo](../../system/typeinfo/), представляющий структуру [TimeSpan](../../system/timespan/). |

## Смотрите также

* Пространство имён [System::Security::Cryptography](../)
* Библиотека [Aspose.Slides](../../)