---
title: GetEntity()
second_title: Aspose.Slides pro C++ API Reference
description: Mapuje URI na objekt, který obsahuje skutečný zdroj.
type: docs
weight: 53
url: /cs/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metoda

Mapuje URI na objekt, který obsahuje skutečný zdroj.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI vrácené voláním [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | Momentálně se nepoužívá. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Typ objektu, který se má vrátit. [XmlPreloadedResolver](../) podporuje objekty Stream a TextReader pro URI, které byly přidány jako [String](../../../system/string/). Pokud požadovaný typ není resolverem podporován, bude vyvolána výjimka. Použijte metodu XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) k určení, zda je určitý **Type** tímto resolverem podporován. |

### Návratová hodnota

Objekt Stream nebo TextReader, který odpovídá skutečnému zdroji.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [Uri](../../../system/uri/)
* Třída [String](../../../system/string/)
* Třída [TypeInfo](../../../system/typeinfo/)
* Třída [XmlPreloadedResolver](../)
* Jmenný prostor [System::Xml::Resolvers](../../)
* Knihovna [Aspose.Slides](../../../)