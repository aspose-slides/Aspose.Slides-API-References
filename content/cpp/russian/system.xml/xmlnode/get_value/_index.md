---
title: get_Value()
second_title: Aspose.Slides для C++ справка API
description: Возвращает значение узла.
type: docs
weight: 14
url: /ru/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() метод


Возвращает значение узла.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```


### Возвращаемое значение

Возвращаемое значение зависит от [XmlNode::get_NodeType](../get_nodetype/) узла: 

| Тип | Значение |
| --- | --- |
| [Attribute](../../../system/attribute/)| Значение атрибута. |
| CDATASection | Содержимое CDATA-раздела. |
| Comment | Содержимое комментария. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. Вы можете использовать XmlElement::InnerText или значения [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/), чтобы получить значение узла элемента. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | Всё содержимое, за исключением цели. |
| [Text](../../../system.text/)| Содержимое текстового узла. |
| SignificantWhitespace | Символы пробельных знаков. Пробел может состоять из одного или более пробельных символов, возвратов каретки, переводов строки или табуляций. |
| Whitespace | Символы пробельных знаков. Пробел может состоять из одного или более пробельных символов, возвратов каретки, переводов строки или табуляций. |
| [XmlDeclaration](../../xmldeclaration/)| Содержимое декларации (то есть всё между `<?xml` и `?>`). |

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [XmlNode](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)