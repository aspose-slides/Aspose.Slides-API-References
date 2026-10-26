---
title: ResolveFunction()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en avledd klass löser den upp en funktionsreferens och returnerar ett IXsltContextFunction som representerar funktionen. IXsltContextFunction används vid körning för att hämta funktionens returvärde.
type: docs
weight: 27
url: /sv/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) method

När den åsidosätts i en avledd klass, löser den upp en funktionsreferens och returnerar ett [IXsltContextFunction](../../ixsltcontextfunction/) som representerar funktionen. [IXsltContextFunction](../../ixsltcontextfunction/) används vid körning för att hämta funktionens returvärde.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Funktionens prefix så som det visas i [XPath](../../../system.xml.xpath/)-uttrycket. |
| name | [String](../../../system/string/) | Funktionens namn. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | En array av argumenttyper för den funktion som löser upp. Detta gör det möjligt att välja mellan metoder med samma namn (t.ex. överlagrade metoder). |

### Returvärde

Ett [IXsltContextFunction](../../ixsltcontextfunction/) som representerar funktionen.

## Se även

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [IXsltContextFunction](../../ixsltcontextfunction/)
* Klass [String](../../../system/string/)
* Klass [XsltContext](../)
* Namnrymd [System::Xml::Xsl](../../)
* Bibliotek [Aspose.Slides](../../../)