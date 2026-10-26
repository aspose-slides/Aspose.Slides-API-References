---
title: ResolveFunction()
second_title: Aspose.Slides для C++ Справочник API
description: При переопределении в производном классе разрешает ссылку на функцию и возвращает IXsltContextFunction, представляющий функцию. IXsltContextFunction используется во время выполнения для получения возвращаемого значения функции.
type: docs
weight: 27
url: /ru/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) метод


When overridden in a derived class, resolves a function reference and returns an [IXsltContextFunction](../../ixsltcontextfunction/) representing the function. The [IXsltContextFunction](../../ixsltcontextfunction/) is used at execution time to get the return value of the function.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Префикс функции, как он отображается в выражении [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | Имя функции. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | Массив типов аргументов функции, которую необходимо разрешить. Это позволяет выбирать между методами с одинаковым именем (например, перегруженными методами). |

### Возвращаемое значение

Объект [IXsltContextFunction](../../ixsltcontextfunction/), представляющий функцию.

## См. также

* Перечисление [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Класс [IXsltContextFunction](../../ixsltcontextfunction/)
* Класс [String](../../../system/string/)
* Класс [XsltContext](../)
* Пространство имён [System::Xml::Xsl](../../)
* Библиотека [Aspose.Slides](../../../)