---
title: Invoke()
second_title: Aspose.Slides для C++ — справочник API
description: Предоставляет метод для вызова функции с заданными аргументами в указанном контексте.
type: docs
weight: 53
url: /ru/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) method

Provides the method to invoke the function with the given arguments in the given context.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | Контекст XSLT для вызова функции. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Аргументы вызова функции. Каждый аргумент является элементом массива. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Узел контекста для вызова функции. |

### Возвращаемое значение

Объект [Object](../../../system/object/) представляет возвращаемое значение функции.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [Object](../../../system/object/)
* Класс [XsltContext](../../xsltcontext/)
* Класс [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Класс [IXsltContextFunction](../)
* Пространство имён [System::Xml::Xsl](../../)
* Библиотека [Aspose.Slides](../../../)