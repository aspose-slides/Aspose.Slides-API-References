---
title: get_LocalName()
second_title: Aspose.Slides для C++ справка API
description: Возвращает локальное имя узла, когда переопределяется в производном классе.
type: docs
weight: 209
url: /ru/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() метод


Возвращает локальное имя узла, когда переопределяется в производном классе.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### Возвращаемое значение

Имя узла без префикса. Например, **LocalName** равно **book** для элемента **<bk:book>**.
## Примечания



Имя, возвращаемое, зависит от [XmlNode::get_NodeType](../get_nodetype/) узла: 

| Тип | Имя |
| --- | --- |
| [Attribute](../../../system/attribute/)| Локальное имя атрибута. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Имя типа документа. |
| Element | Локальное имя элемента. |
| Entity | Имя сущности. |
| EntityReference | Имя ссылки на сущность. |
| Notation | Имя нотации. |
| ProcessingInstruction | Цель инструкции обработки. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## См. также

* Класс [String](../../../system/string/)
* Класс [XmlNode](../)
* Пространство имен [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)