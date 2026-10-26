---
title: GetEntity()
second_title: Aspose.Slides C++ API referencia
description: Leképezi az URI-t egy olyan objektumra, amely a tényleges erőforrást tartalmazza.
type: docs
weight: 53
url: /hu/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) módszer


Leképezi az URI-t egy objektumra, amely a tényleges erőforrást tartalmazza.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Az [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/) hívásból visszakapott URI. |
| role | [String](../../../system/string/) | Jelenleg nincs használatban. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Az visszaadandó objektum típusa. A [XmlPreloadedResolver](../) támogatja a Stream objektumokat és a TextReader objektumokat azokhoz az URI-hez, amelyek [String](../../../system/string/)-ként lettek hozzáadva. Ha a kért típust a feloldó nem támogatja, kivétel keletkezik. Használja a XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) módszert annak meghatározásához, hogy egy adott **Type** támogatott-e ezen a feloldón. |

### Visszatérési érték

Egy Stream vagy TextReader objektum, amely a tényleges forráshoz tartozik.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [Uri](../../../system/uri/)
* Osztály [String](../../../system/string/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [XmlPreloadedResolver](../)
* Névtér [System::Xml::Resolvers](../../)
* Könyvtár [Aspose.Slides](../../../)