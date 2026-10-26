---
title: XmlSchemaValidationFlags
second_title: Aspose.Slides для C++ справочника API
description: Указывает параметры проверки схем, используемые классами XmlSchemaValidator и XmlReader.
type: docs
weight: 1054
url: /ru/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags перечисление


Указывает параметры проверки схем, используемые классами [XmlSchemaValidator](../xmlschemavalidator/) и [XmlReader](../../system.xml/xmlreader/).

```cpp
enum class XmlSchemaValidationFlags
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Не обрабатывать ограничения идентичности, встроенные схемы, подсказки местоположения схемы и не сообщать о предупреждениях проверки схем. |
| ProcessInlineSchema | 1 | Обрабатывать встроенные схемы, обнаруженные во время проверки. |
| ProcessSchemaLocation | 2 | Обрабатывать подсказки местоположения схемы (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**), обнаруженные во время проверки. |
| ReportValidationWarnings | 4 | Сообщать о предупреждениях проверки схем, обнаруженных во время проверки. |
| ProcessIdentityConstraints | 8 | Обрабатывать ограничения идентичности (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**), обнаруженные во время проверки. |
| AllowXmlAttributes | 16 | Разрешать атрибуты xml:*, даже если они не определены в схеме. Атрибуты будут проверяться на основе их типа данных. |

## Смотрите также

* Пространство имен [System::Xml::Schema](../)
* Библиотека [Aspose.Slides](../../)