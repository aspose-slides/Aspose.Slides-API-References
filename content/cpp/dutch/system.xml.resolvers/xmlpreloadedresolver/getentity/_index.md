---
title: GetEntity()
second_title: Aspose.Slides voor C++ API-referentie
description: Koppelt een URI aan een object dat de werkelijke bron bevat.
type: docs
weight: 53
url: /nl/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method


Koppelt een URI aan een object dat de werkelijke bron bevat.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | De URI die is geretourneerd door de [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/)-aanroep. |
| role | [String](../../../system/string/) | Momenteel niet gebruikt. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Het type object dat moet worden geretourneerd. De [XmlPreloadedResolver](../) ondersteunt Stream-objecten en TextReader-objecten voor URI's die zijn toegevoegd als [String](../../../system/string/). Als het gevraagde type niet wordt ondersteund door de resolver, wordt er een uitzondering gegooid. Gebruik de XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo)-methode om te bepalen of een bepaald **Type** wordt ondersteund door deze resolver. |

### Retourwaarde

Een Stream- of TextReader-object dat overeenkomt met de werkelijke bron.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [XmlPreloadedResolver](../)
* Naamruimte [System::Xml::Resolvers](../../)
* Bibliotheek [Aspose.Slides](../../../)