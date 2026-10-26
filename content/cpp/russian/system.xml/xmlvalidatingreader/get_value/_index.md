---
title: get_Value()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает текстовое значение текущего узла.
type: docs
weight: 79
url: /ru/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() метод

Возвращает текстовое значение текущего узла.

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```

### Возвращаемое значение

Возвращаемое значение зависит от XmlValidatingReader::NodeType узла.

## Примечания

В следующей таблице перечислены типы узлов, имеющие значение для возврата. Все остальные типы узлов возвращают [String::Empty](../../../system/string/empty/). 

| Тип узла | Значение |
| --- | --- |
| [Attribute](../../../system/attribute/)| Значение атрибута. |
| CDATA| Содержимое секции CDATA. |
| Comment| Содержимое комментария. |
| DocumentType| Внутреннее подмножество. |
| ProcessingInstruction| Весь контент, исключая цель. |
| SignificantWhitespace| Пробелы между разметкой в модели смешанного содержимого. |
| [Text](../../../system.text/)| Содержимое текстового узла. |
| Whitespace| Пробелы между разметкой. |
| [XmlDeclaration](../../xmldeclaration/)| Содержимое декларации. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlValidatingReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)