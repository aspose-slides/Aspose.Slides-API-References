---
title: ResolveUri()
second_title: Aspose.Slides för C++ API-referens
description: Löser den absoluta URI:n från bas- och relativa URI:er.
type: docs
weight: 66
url: /sv/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) metod

Löser den absoluta URI:n från bas- och relativa URI:er.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Den bas-URI som används för att lösa den relativa URI:n. |
| relativeUri | [String](../../../system/string/) | URI:n som ska lösas. URI:n kan vara absolut eller relativ. Om absolut ersätter detta värde i praktiken **baseUri**-värdet. Om relativ kombineras den med **baseUri** för att skapa en absolut URI. |

### Returvärde

Den absoluta URI:n, eller **nullptr** om den relativa URI:n inte kan lösas.

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [Uri](../../../system/uri/)
* Klass [String](../../../system/string/)
* Klass [XmlUrlResolver](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)