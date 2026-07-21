---
title: get_Value()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает текстовое значение текущего узла.
type: docs
weight: 79
url: /ru/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() метод


Возвращает текстовое значение текущего узла.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```


### Возвращаемое значение

Возвращаемое значение зависит от значения [XmlTextReader::get_NodeType](../get_nodetype/) узла.
## Примечания



В следующей таблице перечислены типы узлов, имеющие возвращаемое значение. Все остальные типы узлов возвращают [String::Empty](../../../system/string/empty/). 

| Тип узла | Значение |
| --- | --- |
| [Attribute](../../../system/attribute/)| Значение атрибута. |
| CDATA| Содержимое секции CDATA. |
| Comment| Содержимое комментария. |
| DocumentType| Внутреннее подмножество. |
| ProcessingInstruction| Полное содержимое, за исключением цели. |
| SignificantWhitespace| Пробельные символы в области `xml:space='preserve'`. |
| [Text](../../../system.text/)| Содержимое текстового узла. |
| Whitespace| Пробельные символы между разметкой. |
| [XmlDeclaration](../../xmldeclaration/)| Содержимое объявления. |


## См. также

* Класс [String](../../../system/string/)
* Класс [XmlTextReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)