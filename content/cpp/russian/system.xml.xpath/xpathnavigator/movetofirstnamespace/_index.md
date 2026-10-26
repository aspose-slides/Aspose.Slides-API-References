---
title: MoveToFirstNamespace()
second_title: Справочник API Aspose.Slides для C++
description: При переопределении в производном классе перемещает XPathNavigator к первому узлу пространства имён, соответствующему указанному XPathNamespaceScope.
type: docs
weight: 560
url: /ru/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) метод

При переопределении в производном классе перемещает [XPathNavigator](../) к первому узлу пространства имён, соответствующему указанному XPathNamespaceScope.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Значение XPathNamespaceScope, описывающее область пространства имён. |

### Возвращаемое значение

**true**, если [XPathNavigator](../) успешно перемещается к первому узлу пространства имён; в противном случае **false**. Если **false**, позиция [XPathNavigator](../) остаётся неизменной.

## XPathNavigator::MoveToFirstNamespace() метод

Перемещает [XPathNavigator](../) к первому узлу пространства имён текущего узла.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```

### Возвращаемое значение

**true**, если [XPathNavigator](../) успешно перемещается к первому узлу пространства имён; в противном случае **false**. Если **false**, позиция [XPathNavigator](../) остаётся неизменной.

## См. также

* Перечисление [XPathNamespaceScope](../../xpathnamespacescope/)
* Класс [XPathNavigator](../)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)