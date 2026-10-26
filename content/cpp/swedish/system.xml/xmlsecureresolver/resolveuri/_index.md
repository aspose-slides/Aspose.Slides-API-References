---
title: ResolveUri()
second_title: Aspose.Slides för C++ API-referens
description: Löser den absoluta URI:n från bas- och relativa URI:er genom att anropa ResolveUri på den underliggande XmlResolver.
type: docs
weight: 40
url: /sv/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) metod


Löser den absoluta URI:n från bas- och relativa URI:er genom att anropa **ResolveUri** på den underliggande [XmlResolver](../../xmlresolver/).

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Bas-URI:n som används för att lösa den relativa URI:n. |
| relativeUri | [String](../../../system/string/) | URI:n att lösa. URI:n kan vara absolut eller relativ. Om den är absolut ersätter detta värde i praktiken värdet **baseUri**. Om den är relativ kombineras den med **baseUri** för att skapa en absolut URI. |

### Returvärde

Den absoluta URI:n eller **nullptr** om den relativa URI:n inte kan lösas (returneras genom att anropa **ResolveUri** på den underliggande [XmlResolver](../../xmlresolver/)).

## Se också

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [Uri](../../../system/uri/)
* Klass [String](../../../system/string/)
* Klass [XmlSecureResolver](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)