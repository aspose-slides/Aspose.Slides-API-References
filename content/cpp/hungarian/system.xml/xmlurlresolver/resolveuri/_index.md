---
title: ResolveUri()
second_title: Aspose.Slides for C++ API referencia
description: Az abszolút URI-t a bázis- és relatív URI-kból oldja fel.
type: docs
weight: 66
url: /hu/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) metódus

Az abszolút URI-t a bázis- és relatív URI-kból oldja fel.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | A relatív URI feloldásához használt alap URI. |
| relativeUri | [String](../../../system/string/) | A feloldandó URI. Az URI lehet abszolút vagy relatív. Ha abszolút, ez az érték lényegében felváltja a **baseUri** értékét. Ha relatív, akkor a **baseUri**-val kombinálva egy abszolút URI-t hoz létre. |

### Visszatérési érték

Az abszolút URI, vagy **nullptr**, ha a relatív URI nem oldható fel.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Uri](../../../system/uri/)
* Osztály [String](../../../system/string/)
* Osztály [XmlUrlResolver](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)