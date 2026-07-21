---
title: get_Name()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает квалифицированное имя узла, когда переопределяется в производном классе.
type: docs
weight: 1
url: /ru/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() метод

Возвращает квалифицированное имя узла, когда переопределяется в производном классе.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```


### Возвращаемое значение

Квалифицированное имя узла.

## Замечания

Возвращаемое имя зависит от [XmlNode::get_NodeType](../get_nodetype/) узла:

| Тип | Имя |
| --- | --- |
| [Attribute](../../../system/attribute/)| Полное имя атрибута. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Имя типа документа. |
| Element | Полное имя элемента. |
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
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)