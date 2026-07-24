---
title: SupportsType()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob der Resolver andere Typen als nur Stream unterstützt.
type: docs
weight: 66
url: /de/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) Methode

Bestimmt, ob der Resolver andere Typen als nur Stream unterstützt.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Der absolute URI zum Prüfen. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Der zurückzugebende Typ. |

### Rückgabewert

**true** wenn der Typ unterstützt wird; andernfalls **false**.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [XmlPreloadedResolver](../)
* Namensraum [System::Xml::Resolvers](../../)
* Bibliothek [Aspose.Slides](../../../)