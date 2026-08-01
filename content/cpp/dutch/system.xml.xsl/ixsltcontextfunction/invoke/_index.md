---
title: Invoke()
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt de methode om de functie aan te roepen met de gegeven argumenten in de gegeven context.
type: docs
weight: 53
url: /nl/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) methode

Biedt de methode om de functie aan te roepen met de gegeven argumenten in de gegeven context.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | De XSLT-context voor de functieroep. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | De argumenten van de functieroep. Elk argument is een element in de array. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | De contextknoop voor de functieroep. |

### Retourwaarde

Een [Object](../../../system/object/) die de retourwaarde van de functie vertegenwoordigt.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Object](../../../system/object/)
* Klasse [XsltContext](../../xsltcontext/)
* Klasse [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Klasse [IXsltContextFunction](../)
* Naamruimte [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)