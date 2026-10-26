---
title: GetEntity()
second_title: Aspose.Slides C++ API referenciája
description: Leképezi egy URI-t egy olyan objektumra, amely a tényleges erőforrást tartalmazza.
type: docs
weight: 53
url: /hu/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) módszer

Leképezi az URI-t egy olyan objektumra, amely a tényleges erőforrást tartalmazza.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Az [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/) hívásból visszakapott URI. |
| role | [String](../../../system/string/) | Jelenleg nincs használva. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | A visszaadandó objektum típusa. A jelenlegi megvalósítás csak Stream objektumokat ad vissza. |

### Visszatérési érték

Egy stream objektum vagy **nullptr**, ha a stream-en kívül más típus van megadva.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [Uri](../../../system/uri/)
* Osztály [String](../../../system/string/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [XmlUrlResolver](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)