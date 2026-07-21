---
title: MoveTo()
second_title: Aspose.Slides для C++ - справочник API
description: При переопределении в производном классе перемещает XPathNavigator в то же положение, что и указанный XPathNavigator.
type: docs
weight: 664
url: /ru/system.xml.xpath/xpathnavigator/moveto/
---
## XPathNavigator::MoveTo(SharedPtr\<XPathNavigator\>) метод

При переопределении в производном классе перемещает [XPathNavigator](../) в то же положение, что и указанный [XPathNavigator](../).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveTo(SharedPtr<XPathNavigator> other)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Экземпляр [XPathNavigator](../), расположеный на узле, к которому вы хотите переместиться. |

### Возвращаемое значение

**true** если [XPathNavigator](../) успешно перемещается в то же положение, что и указанный [XPathNavigator](../); иначе **false**. Если **false**, позиция [XPathNavigator](../) остаётся неизменной.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)