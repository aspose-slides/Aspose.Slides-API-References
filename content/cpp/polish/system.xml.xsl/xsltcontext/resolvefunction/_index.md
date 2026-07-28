---
title: ResolveFunction()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Gdy jest nadpisywana w klasie pochodnej, rozwiązuje odwołanie do funkcji i zwraca IXsltContextFunction reprezentujący funkcję. IXsltContextFunction jest używany w czasie wykonywania do pobrania wartości zwracanej przez funkcję.
type: docs
weight: 27
url: /pl/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) metoda

Gdy jest nadpisywana w klasie pochodnej, rozwiązuje odwołanie do funkcji i zwraca [IXsltContextFunction](../../ixsltcontextfunction/) reprezentujący funkcję. [IXsltContextFunction](../../ixsltcontextfunction/) jest używany w czasie wykonywania do pobrania wartości zwracanej przez funkcję.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Prefiks funkcji tak jak pojawia się w wyrażeniu [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | Nazwa funkcji. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | Tablica typów argumentów dla rozwiązywanej funkcji. Umożliwia wybór pomiędzy metodami o tej samej nazwie (na przykład przeciążone metody). |

### Wartość zwracana

Obiekt [IXsltContextFunction](../../ixsltcontextfunction/) reprezentujący funkcję.

## Zobacz również

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [IXsltContextFunction](../../ixsltcontextfunction/)
* Klasa [String](../../../system/string/)
* Klasa [XsltContext](../)
* Przestrzeń nazw [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)