---
title: SelectSingleNode()
second_title: Справочник API Aspose.Slides для C++
description: Выбирает один узел в XPathNavigator, используя указанный запрос XPath.
type: docs
weight: 781
url: /ru/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) метод

Выбирает один узел в [XPathNavigator](../) с использованием указанного [XPath](../../) запроса.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Объект [String](../../../system/string/), представляющий [XPath](../../) выражение. |

### Возвращаемое значение

Объект [XPathNavigator](../), содержащий первый подходящий узел для указанного запроса [XPath](../../); в противном случае **nullptr**, если результат запроса отсутствует.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) метод

Выбирает один узел в объекте [XPathNavigator](../) с использованием указанного [XPath](../../) запроса и объекта [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), указанного для разрешения пространств имён.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Объект [String](../../../system/string/), представляющий [XPath](../../) выражение. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), используемый для разрешения пространств имён в запросе [XPath](../../). |

### Возвращаемое значение

Объект [XPathNavigator](../), содержащий первый подходящий узел для указанного запроса [XPath](../../); в противном случае **nullptr**, если результат запроса отсутствует.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) метод

Выбирает один узел в [XPathNavigator](../) с использованием указанного [XPathExpression](../../xpathexpression/) объекта.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Объект [XPathExpression](../../xpathexpression/), содержащий скомпилированный запрос [XPath](../../). |

### Возвращаемое значение

Объект [XPathNavigator](../), содержащий первый подходящий узел для указанного запроса [XPath](../../); в противном случае **nullptr**, если результат запроса отсутствует.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XPathNavigator](../)
* Класс [String](../../../system/string/)
* Класс [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Класс [XPathExpression](../../xpathexpression/)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)