---
title: GetEntity()
second_title: Aspose.Slides voor C++ API-referentie
description: Kent een URI toe aan een object dat de daadwerkelijke bron bevat.
type: docs
weight: 27
url: /nl/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) methode

Kent een URI toe aan een object dat de daadwerkelijke bron bevat.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | De URI die wordt geretourneerd door de [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) oproep. |
| role | [String](../../../system/string/) | Momenteel niet gebruikt. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Het type object dat moet worden geretourneerd. De huidige versie retourneert alleen Stream-objecten. |

### Retourwaarde

De stream die wordt geretourneerd door **GetEntity** aan te roepen op de onderliggende [XmlResolver](../../xmlresolver/). Als een type anders dan Stream wordt gespecificeerd, retourneert de methode **nullptr**.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [XmlSecureResolver](../)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)