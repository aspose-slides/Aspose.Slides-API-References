---
title: ResolveUri()
second_title: Aspose.Slides for C++ API referenciája
description: Feloldja az abszolút URI-t az alap és a relatív URI-kból.
type: docs
weight: 40
url: /hu/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) metódus


Feloldja az abszolút URI-t az alap és a relatív URI-kból.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Az alap URI, amelyet a relatív URI feloldásához használnak. |
| relativeUri | [String](../../../system/string/) | A feloldandó URI. Az URI lehet abszolút vagy relatív. Ha abszolút, ez az érték hatékonyan felülírja a **baseUri** értékét. Ha relatív, kombinálódik a **baseUri**-val, hogy egy abszolút URI-t hozzon létre. |

### Visszatérési érték

A [Uri](../../../system/uri/), amely az abszolút URI-t reprezentálja, vagy **nullptr**, ha a relatív URI nem oldható fel.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)