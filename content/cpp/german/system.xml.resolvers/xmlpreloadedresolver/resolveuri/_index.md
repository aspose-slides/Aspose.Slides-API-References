---
title: ResolveUri()
second_title: Aspose.Slides für C++ API-Referenz
description: Löst die absolute URI anhand der Basis- und relativen URIs auf.
type: docs
weight: 40
url: /de/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) Methode


Löst die absolute URI anhand der Basis- und relativen URIs auf.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Die Basis-URI, die zur Auflösung der relativen URI verwendet wird. |
| relativeUri | [String](../../../system/string/) | Die zu resolvierende URI. Die URI kann absolut oder relativ sein. Wenn sie absolut ist, ersetzt dieser Wert effektiv den **baseUri**-Wert. Wenn sie relativ ist, wird sie mit dem **baseUri** kombiniert, um eine absolute URI zu erzeugen. |

### Rückgabewert

Der [Uri](../../../system/uri/) der die absolute URI darstellt oder **nullptr**, wenn die relative URI nicht aufgelöst werden kann.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [XmlPreloadedResolver](../)
* Namensraum [System::Xml::Resolvers](../../)
* Bibliothek [Aspose.Slides](../../../)