---
title: MoveToFirst()
second_title: Справочник API Aspose.Slides для C++
description: Перемещает XPathNavigator к первому соседнему узлу текущего узла.
type: docs
weight: 612
url: /ru/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() метод

Перемещает [XPathNavigator](../) к первому соседнему узлу текущего узла.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```

### Возвращаемое значение

**true** если [XPathNavigator](../) успешно перемещается к первому соседнему узлу текущего узла; **false** если нет первого соседа, или если [XPathNavigator](../) в данный момент находится на узле атрибута. Если [XPathNavigator](../) уже расположен на первом соседнем узле, [XPathNavigator](../) вернёт **true** и не изменит свою позицию. Если [XPathNavigator::MoveToFirst](./) возвращает **false**, поскольку нет первого соседа, или если [XPathNavigator](../) находится на атрибуте, позиция [XPathNavigator](../) остаётся неизменной.

## См. также

* Класс [XPathNavigator](../)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)