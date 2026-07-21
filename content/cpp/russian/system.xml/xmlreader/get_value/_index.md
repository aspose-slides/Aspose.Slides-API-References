---
title: get_Value()
second_title: Aspose.Slides для C++ справочник API
description: При переопределении в производном классе получает текстовое значение текущего узла.
type: docs
weight: 92
url: /ru/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() метод

При переопределении в производном классе получает текстовое значение текущего узла.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```

### Возвращаемое значение

Возвращаемое значение зависит от [XmlReader::get_NodeType](../get_nodetype/) значения узла.

## Замечания

В следующей таблице перечислены типы узлов, имеющие значение для возврата. Все остальные типы узлов возвращают [String::Empty](../../../system/string/empty/). 

| Тип узла | Значение |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Значение атрибута. |
| `CDATA`| Содержимое секции CDATA. |
| `Comment`| Содержимое комментария. |
| `DocumentType`| Внутреннее подмножество. |
| `ProcessingInstruction`| Всё содержимое, за исключением цели. |
| `SignificantWhitespace`| Пробелы между разметкой в смешанной модели содержимого. |
| `[Text](../../../system.text/)`| Содержимое текстового узла. |
| `Whitespace`| Пробелы между разметкой. |
| [XmlDeclaration](../../xmldeclaration/)| Содержимое объявления. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)