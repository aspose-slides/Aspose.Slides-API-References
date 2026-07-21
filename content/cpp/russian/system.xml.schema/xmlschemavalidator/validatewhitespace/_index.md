---
title: ValidateWhitespace()
second_title: Aspose.Slides для C++ справочник API
description: Проверяет, разрешён ли пробельный символ в указанной строке в текущем контексте элемента, и собирает пробельные символы для проверки, если текущий элемент имеет простое содержимое.
type: docs
weight: 196
url: /ru/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) метод

Проверяет, разрешён ли пробельный **строка** в текущем контексте элемента, и собирает пробельные символы для проверки, если текущий элемент имеет простое содержимое.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Белая **строка** для проверки в текущем контексте элемента. |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) метод

Проверяет, разрешён ли пробел, возвращаемый указанным объектом XmlValueGetter, в текущем контексте элемента, и собирает пробельные символы для проверки, если текущий элемент имеет простое содержимое.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Обратный вызов XmlValueGetter, используемый для передачи значения пробельных символов как тип, совместимый с типом XML [Schema](../../) Definition Language (XSD) атрибута. |

## См. также

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Класс [String](../../../system/string/)
* Класс [XmlSchemaValidator](../)
* Пространство имён [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)