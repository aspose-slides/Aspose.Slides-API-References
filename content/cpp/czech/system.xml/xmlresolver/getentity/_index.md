---
title: GetEntity()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Když je přepsána v odvozené třídě, přiřadí URI k objektu, který obsahuje skutečný zdroj.
type: docs
weight: 14
url: /cs/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metoda

Když je přepsána v odvozené třídě, přiřadí URI k objektu, který obsahuje skutečný zdroj.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI vrácené z volání [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | V současné době nepoužívá se. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Typ objektu, který se má vrátit. Současná verze vrací pouze objekty Stream. |

### Návratová hodnota

Objekt stream nebo **nullptr**, pokud je specifikován typ jiný než stream.

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [Uri](../../../system/uri/)
* Třída [String](../../../system/string/)
* Třída [TypeInfo](../../../system/typeinfo/)
* Třída [XmlResolver](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)