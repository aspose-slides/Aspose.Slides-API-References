---
title: GetEntity()
second_title: Aspose.Slides voor C++ API-referentie
description: Koppelt een URI aan een object dat de daadwerkelijke bron bevat.
type: docs
weight: 53
url: /nl/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) methode

Koppelt een URI aan een object dat de daadwerkelijke bron bevat.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | De URI die is geretourneerd door de [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/)-aanroep. |
| role | [String](../../../system/string/) | Momenteel niet gebruikt. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Het type object dat moet worden geretourneerd. De huidige implementatie retourneert alleen Stream-objecten. |

### Retourwaarde

Een stream-object of **nullptr** als een ander type dan stream wordt opgegeven.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [XmlUrlResolver](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)