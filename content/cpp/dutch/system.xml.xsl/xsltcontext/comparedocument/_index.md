---
title: CompareDocument()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, vergelijkt het de basis Uniform Resource Identifiers (URI's) van twee documenten op basis van de volgorde waarin de documenten werden geladen door de XSLT-processor (dat is de XslTransform-klasse).
type: docs
weight: 53
url: /nl/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) methode

When overridden in a derived class, compares the base Uniform Resource Identifiers (URIs) of two documents based upon the order the documents were loaded by the XSLT processor (that is, the [XslTransform](../../xsltransform/) class).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | De basis-URI van het eerste document om te vergelijken. |
| nextbaseUri | [String](../../../system/string/) | De basis-URI van het tweede document om te vergelijken. |

### Retourwaarde

Een geheel getal dat de relatieve volgorde van de twee basis-URI's beschrijft: -1 als **baseUri** voorkomt vóór **nextbaseUri**; 0 als de twee basis-URI's identiek zijn; en 1 als **baseUri** voorkomt na **nextbaseUri**.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XsltContext](../)
* Naamruimte [System::Xml::Xsl](../../)
* Bibliotheek [Aspose.Slides](../../../)