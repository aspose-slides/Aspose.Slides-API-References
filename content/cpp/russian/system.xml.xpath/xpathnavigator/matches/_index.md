---
title: Matches()
second_title: Aspose.Slides для C++ API Reference
description: Определяет, соответствует ли текущий узел указанному XPathExpression.
type: docs
weight: 820
url: /ru/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) метод


Определяет, совпадает ли текущий узел с указанным [XPathExpression](../../xpathexpression/).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Объект [XPathExpression](../../xpathexpression/), содержащий скомпилированное выражение [XPath](../../). |

### Возвращаемое значение

**true** если текущий узел совпадает с [XPathExpression](../../xpathexpression/); в противном случае **false**.

## XPathNavigator::Matches(String) метод


Определяет, совпадает ли текущий узел с указанным [XPath](../../) выражением.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Выражение [XPath](../../). |

### Возвращаемое значение

**true** если текущий узел совпадает с указанным [XPath](../../) выражением; в противном случае **false**.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XPathExpression](../../xpathexpression/)
* Класс [XPathNavigator](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)