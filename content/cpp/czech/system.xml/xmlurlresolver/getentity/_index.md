---
title: GetEntity()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Mapuje URI na objekt, který obsahuje skutečný zdroj.
type: docs
weight: 53
url: /cs/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metoda

Mapuje URI na objekt, který obsahuje skutečný zdroj.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI vrácené voláním [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | Momentálně se nepoužívá. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Typ objektu, který má být vrácen. Současná implementace vrací pouze objekty typu Stream. |

### Návratová hodnota

Objekt stream nebo **nullptr**, pokud je specifikován typ jiný než stream.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [Uri](../../../system/uri/)
* Třída [String](../../../system/string/)
* Třída [TypeInfo](../../../system/typeinfo/)
* Třída [XmlUrlResolver](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)