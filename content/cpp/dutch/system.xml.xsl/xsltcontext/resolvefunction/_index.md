---
title: ResolveFunction()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, lost een functiereferentie op en retourneert een IXsltContextFunction die de functie voorstelt. De IXsltContextFunction wordt tijdens de uitvoering gebruikt om de retourwaarde van de functie te verkrijgen.
type: docs
weight: 27
url: /nl/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) methode


Wanneer overschreven in een afgeleide klasse, lost een functiereferentie op en retourneert een [IXsltContextFunction](../../ixsltcontextfunction/) die de functie voorstelt. De [IXsltContextFunction](../../ixsltcontextfunction/) wordt tijdens de uitvoering gebruikt om de retourwaarde van de functie te verkrijgen.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Het voorvoegsel van de functie zoals het voorkomt in de [XPath](../../../system.xml.xpath/)-expressie. |
| name | [String](../../../system/string/) | De naam van de functie. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | Een array van argumenttypen voor de functie die wordt opgezocht. Hierdoor kunt u kiezen tussen methoden met dezelfde naam (bijvoorbeeld overladen methoden). |

### Retourwaarde

Een [IXsltContextFunction](../../ixsltcontextfunction/) die de functie voorstelt.

## Zie ook

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IXsltContextFunction](../../ixsltcontextfunction/)
* Klasse [String](../../../system/string/)
* Klasse [XsltContext](../)
* Naamruimte [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)