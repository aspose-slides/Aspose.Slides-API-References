---
title: ResolveUri()
second_title: Aspose.Slides voor C++ API-referentie
description: Berekent de absolute URI op basis van de basis- en relatieve URI's.
type: docs
weight: 66
url: /nl/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) methode

Berekent de absolute URI op basis van de basis- en relatieve URI's.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | De basis-URI die wordt gebruikt om de relatieve URI op te lossen. |
| relativeUri | [String](../../../system/string/) | De URI die moet worden opgelost. De URI kan absoluut of relatief zijn. Als absoluut, vervangt deze waarde effectief de **baseUri**-waarde. Als relatief, combineert deze met de **baseUri** om een absolute URI te vormen. |

### Retourwaarde

De absolute URI, of **nullptr** als de relatieve URI niet kan worden opgelost.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlUrlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)