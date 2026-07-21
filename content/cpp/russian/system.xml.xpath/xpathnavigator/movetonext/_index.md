---
title: MoveToNext()
second_title: Aspose.Slides для C++ справочник API
description: При переопределении в производном классе перемещает XPathNavigator к следующему узлу-соседу текущего узла.
type: docs
weight: 586
url: /ru/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() метод

Когда переопределяется в производном классе, перемещает [XPathNavigator](../) к следующему узлу-соседу текущего узла.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```

### Возвращаемое значение

**true**, если [XPathNavigator](../) успешно переместился к следующему узлу-соседу; в противном случае **false**, если больше нет соседних узлов или если [XPathNavigator](../) в данный момент находится на узле-атрибуте. Если **false**, положение [XPathNavigator](../) останется без изменений.

## XPathNavigator::MoveToNext(String, String) метод

Перемещает [XPathNavigator](../) к следующему узлу-соседу с указанным локальным именем и URI пространства имён.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя следующего узла-соседа, к которому следует переместиться. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён следующего узла-соседа, к которому следует переместиться. |

### Возвращаемое значение

**true**, если [XPathNavigator](../) успешно переместился к следующему узлу-соседу; **false**, если больше нет соседних узлов или если [XPathNavigator](../) в данный момент находится на узле-атрибуте. Если **false**, положение [XPathNavigator](../) останется без изменений.

## XPathNavigator::MoveToNext(XPathNodeType) метод

Перемещает [XPathNavigator](../) к следующему узлу-соседу текущего узла, который соответствует указанному XPathNodeType.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType соседнего узла, к которому следует переместиться. |

### Возвращаемое значение

**true**, если [XPathNavigator](../) успешно переместился к следующему узлу-соседу; в противном случае **false**, если больше нет соседних узлов или если [XPathNavigator](../) в данный момент находится на узле-атрибуте. Если **false**, положение [XPathNavigator](../) останется без изменений.

## См. также

* Перечисление [XPathNodeType](../../xpathnodetype/)
* Класс [XPathNavigator](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)