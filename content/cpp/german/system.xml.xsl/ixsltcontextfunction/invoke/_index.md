---
title: Invoke()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die Methode bereit, um die Funktion mit den angegebenen Argumenten im angegebenen Kontext aufzurufen.
type: docs
weight: 53
url: /de/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) Methode

Stellt die Methode bereit, um die Funktion mit den angegebenen Argumenten im angegebenen Kontext aufzurufen.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | Der XSLT-Kontext für den Funktionsaufruf. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Die Argumente des Funktionsaufrufs. Jedes Argument ist ein Element im Array. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Der Kontextknoten für den Funktionsaufruf. |

### Rückgabewert

Ein [Object](../../../system/object/) der den Rückgabewert der Funktion darstellt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Object](../../../system/object/)
* Klasse [XsltContext](../../xsltcontext/)
* Klasse [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Klasse [IXsltContextFunction](../)
* Namensraum [System::Xml::Xsl](../../)
* Bibliothek [Aspose.Slides](../../../)