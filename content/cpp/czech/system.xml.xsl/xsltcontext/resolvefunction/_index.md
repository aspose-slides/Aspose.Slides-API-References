---
title: ResolveFunction()
second_title: Aspose.Slides pro C++ API Reference
description: Když je přepsána v odvozené třídě, vyřeší odkaz na funkci a vrátí IXsltContextFunction představující funkci. IXsltContextFunction se používá během vykonání k získání návratové hodnoty funkce.
type: docs
weight: 27
url: /cs/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) metoda


Když je přepsána v odvozené třídě, vyřeší odkaz na funkci a vrátí [IXsltContextFunction](../../ixsltcontextfunction/) představující funkci. [IXsltContextFunction](../../ixsltcontextfunction/) se používá během vykonání k získání návratové hodnoty funkce.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Předpona funkce tak, jak se objevuje ve výrazu [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | Název funkce. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | Pole typů argumentů pro řešenou funkci. Umožňuje vybrat mezi metodami se stejným názvem (například přetížené metody). |

### Návratová hodnota

[IXsltContextFunction](../../ixsltcontextfunction/) představující funkci.

## Viz také

* Výčet [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Třída [IXsltContextFunction](../../ixsltcontextfunction/)
* Třída [String](../../../system/string/)
* Třída [XsltContext](../)
* Jmenný prostor [System::Xml::Xsl](../../)
* Knihovna [Aspose.Slides](../../../)