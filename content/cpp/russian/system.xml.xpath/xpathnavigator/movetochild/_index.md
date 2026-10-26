---
title: MoveToChild()
second_title: Справочник API Aspose.Slides для C++
description: Перемещает XPathNavigator к дочернему узлу с указанными локальным именем и URI пространства имён.
type: docs
weight: 690
url: /ru/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) метод

Moves the [XPathNavigator](../) to the child node with the local name and namespace URI specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя дочернего узла, к которому следует переместиться. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён дочернего узла, к которому следует переместиться. |

### Возвращаемое значение

**true** если [XPathNavigator](../) успешно перемещается к дочернему узлу; в противном случае **false**. Если **false**, позиция [XPathNavigator](../) остаётся неизменной.

## XPathNavigator::MoveToChild(XPathNodeType) метод

Moves the [XPathNavigator](../) to the child node of the XPathNodeType specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType дочернего узла, к которому следует переместиться. |

### Возвращаемое значение

**true** если [XPathNavigator](../) успешно перемещается к дочернему узлу; в противном случае **false**. Если **false**, позиция [XPathNavigator](../) остаётся неизменной.

## См. также

* Перечисление [XPathNodeType](../../xpathnodetype/)
* Класс [String](../../../system/string/)
* Класс [XPathNavigator](../)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)