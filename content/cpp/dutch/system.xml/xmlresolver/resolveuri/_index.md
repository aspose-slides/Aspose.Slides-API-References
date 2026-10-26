---
title: ResolveUri()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer deze wordt overschreven in een afgeleide klasse, lost hij de absolute URI op basis van de basis- en relatieve URI's.
type: docs
weight: 27
url: /nl/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) method

Wanneer deze wordt overschreven in een afgeleide klasse, lost hij de absolute URI op basis van de basis- en relatieve URI's.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | De basis-URI die wordt gebruikt om de relatieve URI op te lossen. |
| relativeUri | [String](../../../system/string/) | De op te lossen URI. De URI kan absoluut of relatief zijn. Als deze absoluut is, vervangt deze waarde daadwerkelijk de **baseUri**-waarde. Als deze relatief is, wordt deze gecombineerd met de **baseUri** om een absolute URI te vormen. |

### Retourwaarde

De absolute URI of **nullptr** als de relatieve URI niet kan worden opgelost.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [XmlResolver](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)