---
title: GetEntity()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, koppelt het een URI aan een object dat de daadwerkelijke bron bevat.
type: docs
weight: 14
url: /nl/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method


Wanneer overschreven in een afgeleide klasse, koppelt het een URI aan een object dat de werkelijke bron bevat.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | De URI geretourneerd door de [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/)-aanroep. |
| role | [String](../../../system/string/) | Momenteel niet gebruikt. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Het type object dat moet worden geretourneerd. De huidige versie retourneert alleen Stream-objecten. |

### Retourwaarde

Een stream-object of **nullptr** als een ander type dan stream is opgegeven.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [XmlResolver](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)