---
title: SupportsType()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of de resolver andere types ondersteunt dan alleen Stream.
type: docs
weight: 66
url: /nl/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) methode

Bepaalt of de resolver andere Types ondersteunt dan alleen Stream.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | De absolute URI om te controleren. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | De Type om te retourneren. |

### Retourwaarde

**true** als de Type wordt ondersteund; anders **false**.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Bibliotheek [Aspose.Slides](../../../)