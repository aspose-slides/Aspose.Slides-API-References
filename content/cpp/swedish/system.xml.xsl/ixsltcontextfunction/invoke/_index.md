---
title: Invoke()
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller metoden för att anropa funktionen med de angivna argumenten i den givna kontexten.
type: docs
weight: 53
url: /sv/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) metod


Tillhandahåller metoden för att anropa funktionen med de angivna argumenten i den givna kontexten.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | XSLT-kontexten för funktionsanropet. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Argumenten för funktionsanropet. Varje argument är ett element i arrayen. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Kontextnoden för funktionsanropet. |

### Returvärde

Ett [Object](../../../system/object/) som representerar returvärdet för funktionen.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Object](../../../system/object/)
* Klass [XsltContext](../../xsltcontext/)
* Klass [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Klass [IXsltContextFunction](../)
* Namnrymd [System::Xml::Xsl](../../)
* Bibliotek [Aspose.Slides](../../../)