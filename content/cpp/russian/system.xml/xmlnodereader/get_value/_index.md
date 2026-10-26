---
title: get_Value()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает текстовое значение текущего узла.
type: docs
weight: 79
url: /ru/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() метод

Возвращает текстовое значение текущего узла.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```

### Возвращаемое значение

Возвращаемое значение зависит от [XmlNodeReader::get_NodeType](../get_nodetype/) узла.

## Примечания

В следующей таблице перечислены типы узлов, у которых есть значение для возврата. Все остальные типы узлов возвращают [String::Empty](../../../system/string/empty/).

| Тип узла | Значение |
| --- | --- |
| [Attribute](../../../system/attribute/)| Значение атрибута. |
| CDATA| Содержимое секции CDATA. |
| Comment| Содержимое комментария. |
| DocumentType| Внутреннее подмножество. |
| ProcessingInstruction| Весь контент, за исключением цели. |
| SignificantWhitespace| Пробелы между разметкой в модели смешанного контента. |
| [Text](../../../system.text/)| Содержимое текстового узла. |
| Whitespace| Пробелы между разметкой. |
| [XmlDeclaration](../../xmldeclaration/)| Содержимое декларации. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlNodeReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)