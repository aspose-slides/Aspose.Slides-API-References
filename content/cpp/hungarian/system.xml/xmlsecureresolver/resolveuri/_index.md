---
title: ResolveUri()
second_title: Aspose.Slides C++ API Referencia
description: Az abszolút URI-t az alap- és relatív URI-kből oldja fel a ResolveUri hívásával az alapul szolgáló XmlResolver-en.
type: docs
weight: 40
url: /hu/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) metódus

Az alap- és relatív URI-k alapján az abszolút URI-t a **ResolveUri** meghívásával oldja fel az alapul szolgáló [XmlResolver](../../xmlresolver/).

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Az alap URI, amelyet a relatív URI feloldásához használnak. |
| relativeUri | [String](../../../system/string/) | A feloldandó URI. Az URI lehet abszolút vagy relatív. Ha abszolút, ez az érték lényegében felülírja a **baseUri** értékét. Ha relatív, a **baseUri**-val kombinálva abszolút URI-t hoz létre. |

### Visszatérési érték

Az abszolút URI vagy **nullptr**, ha a relatív URI-t nem lehet feloldani (a **ResolveUri** meghívásával az alapul szolgáló [XmlResolver](../../xmlresolver/) esetén).

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Uri](../../../system/uri/)
* Osztály [String](../../../system/string/)
* Osztály [XmlSecureResolver](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)