---
title: GetEntity()
second_title: Aspose.Slides C++ API hivatkozás
description: Ha egy származtatott osztályban felülírják, egy URI-t egy olyan objektumhoz rendel, amely a tényleges erőforrást tartalmazza.
type: docs
weight: 14
url: /hu/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metódus

Amikor egy származtatott osztályban felülírják, egy URI-t egy olyan objektumhoz rendel, amely a tényleges erőforrást tartalmazza.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Az [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) hívásból visszaadott URI. |
| role | [String](../../../system/string/) | Jelenleg nincs használatban. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | A visszaadandó objektum típusa. A jelenlegi verzió csak Stream objektumokat ad vissza. |

### Visszatérési érték

Egy stream objektum, vagy **nullptr**, ha a streamen kívül más típus van megadva.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)