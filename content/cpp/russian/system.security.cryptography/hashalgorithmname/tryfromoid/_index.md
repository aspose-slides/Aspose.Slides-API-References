---
title: TryFromOid()
second_title: Aspose.Slides для C++ API Reference
description: Попробуйте создать HashAlgorithmName из значения OID.
type: docs
weight: 66
url: /ru/system.security.cryptography/hashalgorithmname/tryfromoid/
---
## HashAlgorithmName::TryFromOid(const String&, HashAlgorithmName&) метод

Попробуйте создать [HashAlgorithmName](../) из значения OID.

```cpp
static bool System::Security::Cryptography::HashAlgorithmName::TryFromOid(const String &oid_value, HashAlgorithmName &value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| oid_value | const [String](../../../system/string/)\& | Значение OID. |
| value | [HashAlgorithmName](../)\& | Вывод [HashAlgorithmName](../). |

### Возвращаемое значение

true если указанный OID является действительным алгоритмом хеша, иначе - false.

## См. также

* Класс [String](../../../system/string/)
* Структура [HashAlgorithmName](../)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)