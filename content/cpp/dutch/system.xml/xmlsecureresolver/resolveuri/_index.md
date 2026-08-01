---
title: ResolveUri()
second_title: Aspose.Slides voor C++ API Referentie
description: Lost de absolute URI op vanuit de basis- en relatieve URI's door ResolveUri aan te roepen op de onderliggende XmlResolver.
type: docs
weight: 40
url: /nl/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) methode

Lost de absolute URI op vanuit de basis- en relatieve URI's door **ResolveUri** aan te roepen op de onderliggende [XmlResolver](../../xmlresolver/).

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | De basis-URI die wordt gebruikt om de relatieve URI op te lossen. |
| relativeUri | [String](../../../system/string/) | De op te lossen URI. De URI kan absoluut of relatief zijn. Als absoluut, vervangt deze waarde effectief de **baseUri**-waarde. Als relatief, wordt deze gecombineerd met de **baseUri** om een absolute URI te maken. |

### Retourwaarde

De absolute URI of **nullptr** als de relatieve URI niet kan worden opgelost (geretourneerd door **ResolveUri** aan te roepen op de onderliggende [XmlResolver](../../xmlresolver/)).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [XmlSecureResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)