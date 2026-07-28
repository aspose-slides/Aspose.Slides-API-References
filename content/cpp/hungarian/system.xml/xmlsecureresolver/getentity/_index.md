---
title: GetEntity()
second_title: Aspose.Slides C++ API referenciája
description: Egy URI-t egy olyan objektumra képez le, amely a tényleges erőforrást tartalmazza.
type: docs
weight: 27
url: /hu/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metódus

Egy URI-t egy olyan objektumra térképez, amely a tényleges erőforrást tartalmazza.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Az URI, amely a [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) hívásból kerül visszaadásra. |
| role | [String](../../../system/string/) | Jelenleg nincs használatban. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | A visszaadandó objektum típusa. A jelenlegi verzió csak Stream objektumokat ad vissza. |

### Visszatérési érték

A folyam, amely a háttérben lévő [XmlResolver](../../xmlresolver/) **GetEntity** metódusának meghívásával kerül visszaadásra. Ha a Stream-tól eltérő típus van megadva, a metódus **nullptr**-t ad vissza.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [Uri](../../../system/uri/)
* Osztály [String](../../../system/string/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [XmlSecureResolver](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)