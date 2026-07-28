---
title: ResolveUri()
second_title: Aspose.Slides for C++ API Referencia
description: Ha egy származtatott osztályban felül van írva, akkor a bázis és relatív URI-kból állítja elő a teljes URI-t.
type: docs
weight: 27
url: /hu/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) metódus

Ha egy származtatott osztályban felül van íratva, akkor a bázis és relatív URI-kból állítja elő a teljes URI-t.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | A relatív URI feloldásához használt alap URI. |
| relativeUri | [String](../../../system/string/) | A feloldandó URI. Az URI lehet abszolút vagy relatív. Ha abszolút, ez az érték hatékonyan felülírja a **baseUri** értékét. Ha relatív, a **baseUri**-t kombinálva létrehoz egy abszolút URI-t. |

### Visszatérési érték

A teljes URI vagy **nullptr**, ha a relatív URI nem oldható fel.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)