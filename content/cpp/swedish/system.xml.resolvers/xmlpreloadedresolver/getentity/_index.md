---
title: GetEntity()
second_title: Aspose.Slides för C++ API-referens
description: Kopplar en URI till ett objekt som innehåller den faktiska resursen.
type: docs
weight: 53
url: /sv/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metod

Kopplar en URI till ett objekt som innehåller den faktiska resursen.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Den URI som returnerades från [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/)-anropet. |
| role | [String](../../../system/string/) | Används för närvarande inte. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Typen av objekt att returnera. [XmlPreloadedResolver](../) stöder Stream-objekt och TextReader-objekt för URI:er som lades till som [String](../../../system/string/). Om den begärda typen inte stöds av resolvern kastas ett undantag. Använd XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) metod för att avgöra om en viss **Type** stöds av denna resolver. |

### Returvärde

Ett Stream- eller TextReader-objekt som motsvarar den faktiska källan.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [Uri](../../../system/uri/)
* Klass [String](../../../system/string/)
* Klass [TypeInfo](../../../system/typeinfo/)
* Klass [XmlPreloadedResolver](../)
* Namnrymd [System::Xml::Resolvers](../../)
* Bibliotek [Aspose.Slides](../../../)