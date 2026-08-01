---
title: ResolveUri()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt de absolute URI op basis van de basis- en relatieve URI's.
type: docs
weight: 40
url: /nl/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) methode

Bepaalt de absolute URI op basis van de basis- en relatieve URI's.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | De basis-URI die wordt gebruikt om de relatieve URI op te lossen. |
| relativeUri | [String](../../../system/string/) | De te resolveren URI. De URI kan absoluut of relatief zijn. Als absoluut, vervangt deze waarde effectief de **baseUri**-waarde. Als relatief, combineert deze met de **baseUri** om een absolute URI te vormen. |

### Returnwaarde

De [Uri](../../../system/uri/) die de absolute URI vertegenwoordigt of **nullptr** als de relatieve URI niet kan worden opgelost.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [XmlPreloadedResolver](../)
* Naamruimte [System::Xml::Resolvers](../../)
* Bibliotheek [Aspose.Slides](../../../)