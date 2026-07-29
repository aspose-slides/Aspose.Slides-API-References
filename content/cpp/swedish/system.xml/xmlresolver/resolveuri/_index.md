---
title: ResolveUri()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en härledd klass löser den den absoluta URI:n från bas- och relativa URI:er.
type: docs
weight: 27
url: /sv/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) metod


När den åsidosätts i en härledd klass, löser den den absoluta URI:n från bas- och relativa URI:er.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Bas-URI:n som används för att lösa den relativa URI:n. |
| relativeUri | [String](../../../system/string/) | URI:n att lösa. URI:n kan vara absolut eller relativ. Om den är absolut ersätter detta värde effektivt värdet **baseUri**. Om den är relativ kombineras den med **baseUri** för att skapa en absolut URI. |

### Returvärde

Det absoluta URI:n eller **nullptr** om den relativa URI:n inte kan lösas.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)