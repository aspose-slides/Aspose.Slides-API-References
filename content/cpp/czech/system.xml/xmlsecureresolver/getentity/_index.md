---
title: GetEntity()
second_title: Aspose.Slides pro C++ API Reference
description: Mapuje URI na objekt, který obsahuje skutečný zdroj.
type: docs
weight: 27
url: /cs/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metoda

Mapuje URI na objekt, který obsahuje skutečný zdroj.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI, který je vrácen voláním [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | Momentálně se nepoužívá. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Typ objektu, který se má vrátit. Aktuální verze vrací pouze objekty Stream. |

### Návratová hodnota

Stream vrácený voláním **GetEntity** na podkladovém [XmlResolver](../../xmlresolver/). Pokud je zadán typ jiný než Stream, metoda vrátí **nullptr**.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [Uri](../../../system/uri/)
* Třída [String](../../../system/string/)
* Třída [TypeInfo](../../../system/typeinfo/)
* Třída [XmlSecureResolver](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)