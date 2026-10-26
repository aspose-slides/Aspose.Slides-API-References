---
title: ResolveUri()
second_title: Aspose.Slides för C++ API-referens
description: Löser den absoluta URI:n från den grundläggande och relativa URI:erna.
type: docs
weight: 40
url: /sv/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) metod

Löser den absoluta URI:n från den grundläggande och relativa URI:erna.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Den grundläggande URI som används för att lösa den relativa URI:n. |
| relativeUri | [String](../../../system/string/) | Den URI som ska lösas. URI kan vara absolut eller relativ. Om absolut ersätter detta värde effektivt **baseUri**-värdet. Om relativ kombineras den med **baseUri** för att skapa en absolut URI. |

### Returvärde

Den [Uri](../../../system/uri/) som representerar den absoluta URI:n eller **nullptr** om den relativa URI:n inte kan lösas.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Uri](../../../system/uri/)
* Klass [String](../../../system/string/)
* Klass [XmlPreloadedResolver](../)
* Namnrymd [System::Xml::Resolvers](../../)
* Bibliotek [Aspose.Slides](../../../)