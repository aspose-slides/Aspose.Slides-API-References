---
title: PreserveWhitespace()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer deze wordt overschreven in een afgeleide klasse, evalueert hij of witruimteknooppunten behouden moeten blijven of moeten worden verwijderd voor de gegeven context.
type: docs
weight: 40
url: /nl/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) methode

Wanneer deze wordt overschreven in een afgeleide klasse, evalueert hij of witruimteknooppunten behouden moeten blijven of moeten worden verwijderd voor de gegeven context.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Het witruimteknooppunt dat behouden of verwijderd moet worden in de huidige context. |

### Retourwaarde

**true** als de witruimte behouden moet blijven; **false** als de witruimte verwijderd moet worden.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Klasse [XsltContext](../)
* Naamruimte [System::Xml::Xsl](../../)
* Bibliotheek [Aspose.Slides](../../../)