---
title: ResolveVariable()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, lost het een variabelereferentie op en retourneert een IXsltContextVariable die de variabele vertegenwoordigt.
type: docs
weight: 14
url: /nl/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) methode


Wanneer overschreven in een afgeleide klasse, lost een variabelereferentie op en retourneert een [IXsltContextVariable](../../ixsltcontextvariable/) die de variabele vertegenwoordigt.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | De prefix van de variabele zoals deze verschijnt in de [XPath](../../../system.xml.xpath/) expressie. |
| name | [String](../../../system/string/) | De naam van de variabele. |

### Retourwaarde

Een [IXsltContextVariable](../../ixsltcontextvariable/) die de variabele tijdens runtime vertegenwoordigt.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IXsltContextVariable](../../ixsltcontextvariable/)
* Klasse [String](../../../system/string/)
* Klasse [XsltContext](../)
* Naamruimte [System::Xml::Xsl](../../)
* Bibliotheek [Aspose.Slides](../../../)