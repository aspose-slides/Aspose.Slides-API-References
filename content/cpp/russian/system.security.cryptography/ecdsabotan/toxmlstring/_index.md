---
title: ToXmlString()
second_title: Aspose.Slides для C++ справочник API
description: Экспортирует все параметры в формате XML. Не реализовано.
type: docs
weight: 157
url: /ru/system.security.cryptography/ecdsabotan/toxmlstring/
---
## ECDsaBotan::ToXmlString(bool) метод


Экспортирует все параметры в формате XML. Не реализовано.

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(bool include_private_parameters) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| include_private_parameters | **bool** | True — экспортировать как закрытые, так и открытые параметры, false — экспортировать только открытые параметры. |

### Возвращаемое значение

XML-закодированные параметры.

## ECDsaBotan::ToXmlString(ECKeyXmlFormat) метод


Экспортирует все параметры в формате XML.

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(ECKeyXmlFormat format)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | [ECKeyXmlFormat](../../eckeyxmlformat/) | Формат результирующей строки XML. |

### Возвращаемое значение

XML-закодированные параметры.

## См. также

* Перечисление [ECKeyXmlFormat](../../eckeyxmlformat/)
* Класс [String](../../../system/string/)
* Класс [ECDsaBotan](../)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)