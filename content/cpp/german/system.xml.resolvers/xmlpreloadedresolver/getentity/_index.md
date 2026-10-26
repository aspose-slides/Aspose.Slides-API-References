---
title: GetEntity()
second_title: Aspose.Slides für C++ API-Referenz
description: Ordnet einen URI einem Objekt zu, das die eigentliche Ressource enthält.
type: docs
weight: 53
url: /de/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) Methode

Ordnet einen URI einem Objekt zu, das die eigentliche Ressource enthält.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Der URI, der vom Aufruf [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/) zurückgegeben wird. |
| role | [String](../../../system/string/) | Derzeit nicht verwendet. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Der Typ des zurückzugebenden Objekts. Der [XmlPreloadedResolver](../) unterstützt Stream-Objekte und TextReader-Objekte für URIs, die als [String](../../../system/string/) hinzugefügt wurden. Wenn der angeforderte Typ vom Resolver nicht unterstützt wird, wird eine Ausnahme ausgelöst. Verwenden Sie die XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) Methode, um zu bestimmen, ob ein bestimmter **Typ** von diesem Resolver unterstützt wird. |

### Rückgabewert

Ein Stream- oder TextReader-Objekt, das der tatsächlichen Quelle entspricht.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)