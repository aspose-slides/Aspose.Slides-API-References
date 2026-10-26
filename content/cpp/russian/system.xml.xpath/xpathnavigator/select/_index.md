---
title: Select()
second_title: Aspose.Slides для C++ API справочник
description: Выбирает набор узлов, используя указанное XPath-выражение.
type: docs
weight: 794
url: /ru/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) метод


Выбирает набор узлов, используя указанное [XPath](../../) выражение.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Объект [String](../../../system/string/), представляющий [XPath](../../) выражение. |

### Return Value

Объект [XPathNodeIterator](../../xpathnodeiterator/), указывающий на выбранный набор узлов.

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) метод


Выбирает набор узлов, используя указанное [XPath](../../) выражение и объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), указанный для разрешения префиксов пространств имён.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Объект [String](../../../system/string/), представляющий [XPath](../../) выражение. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), используемый для разрешения префиксов пространств имён. |

### Return Value

Объект [XPathNodeIterator](../../xpathnodeiterator/), указывающий на выбранный набор узлов.

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) метод


Выбирает набор узлов, используя указанное [XPathExpression](../../xpathexpression/).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Объект [XPathExpression](../../xpathexpression/), содержащий скомпилированный запрос [XPath](../../). |

### Return Value

Объект [XPathNodeIterator](../../xpathnodeiterator/), указывающий на выбранный набор узлов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XPathNodeIterator](../../xpathnodeiterator/)
* Класс [String](../../../system/string/)
* Класс [XPathNavigator](../)
* Класс [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Класс [XPathExpression](../../xpathexpression/)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)