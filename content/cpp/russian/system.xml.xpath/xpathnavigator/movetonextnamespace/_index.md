---
title: MoveToNextNamespace()
second_title: Aspose.Slides для C++ справочник API
description: При переопределении в производном классе перемещает XPathNavigator к следующему узлу пространства имен, соответствующему указанному XPathNamespaceScope.
type: docs
weight: 573
url: /ru/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) метод

При переопределении в производном классе перемещает [XPathNavigator](../) к следующему узлу пространства имен, соответствующему указанному XPathNamespaceScope.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Значение XPathNamespaceScope, описывающее область пространства имен. |

### Возвращаемое значение

**true** если [XPathNavigator](../) успешно перемещается к следующему узлу пространства имен; в противном случае **false**. Если **false**, позиция [XPathNavigator](../) остаётся неизменной.

## XPathNavigator::MoveToNextNamespace() метод

Перемещает [XPathNavigator](../) к следующему узлу пространства имен.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```

### Возвращаемое значение

**true** если [XPathNavigator](../) успешно перемещается к следующему узлу пространства имен; в противном случае **false**. Если **false**, позиция [XPathNavigator](../) остаётся неизменной.

## См. также

* Перечисление [XPathNamespaceScope](../../xpathnamespacescope/)
* Класс [XPathNavigator](../)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)