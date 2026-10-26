---
title: ValidateText()
second_title: Aspose.Slides для C++ справка по API
description: Проверяет, разрешена ли указанная строка текста в текущем контексте элемента, и собирает текст для проверки, если текущий элемент имеет простое содержимое.
type: docs
weight: 183
url: /ru/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) метод


Проверяет, разрешена ли указанная **строка** текста в текущем контексте элемента, и собирает текст для проверки, если текущий элемент имеет простое содержимое.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Текстовая **строка** для проверки в текущем контексте элемента. |

## XmlSchemaValidator::ValidateText(XmlValueGetter) метод


Проверяет, разрешён ли текст, возвращаемый указанным объектом XmlValueGetter, в текущем контексте элемента, и собирает текст для проверки, если текущий элемент имеет простое содержимое.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Обратный вызов XmlValueGetter, используемый для передачи текстового значения в виде типа, совместимого с типом XML [Schema](../../) Definition Language (XSD) атрибута. |

## См. также

* Типedef [XmlValueGetter](../../xmlvaluegetter/)
* Класс [String](../../../system/string/)
* Класс [XmlSchemaValidator](../)
* Пространство имен [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)