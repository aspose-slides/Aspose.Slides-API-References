---
title: get_Current()
second_title: Справочник API Aspose.Slides для C++
description: При переопределении в производном классе возвращает объект XPathNavigator для этого XPathNodeIterator, расположенный на текущем узле контекста.
type: docs
weight: 1
url: /ru/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() метод

При переопределении в производном классе возвращает объект [XPathNavigator](../../xpathnavigator/) для этого [XPathNodeIterator](../), расположенный на текущем узле контекста.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```

### Возвращаемое значение

Объект [XPathNavigator](../../xpathnavigator/), расположенный на узле контекста, из которого был выбран набор узлов. Метод [XPathNodeIterator::MoveNext](../movenext/) должен быть вызван, чтобы переместить [XPathNodeIterator](../) к первому узлу в выбранном наборе.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XPathNavigator](../../xpathnavigator/)
* Класс [XPathNodeIterator](../)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)