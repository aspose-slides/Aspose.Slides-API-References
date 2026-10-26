---
title: ResolveUri()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn in einer abgeleiteten Klasse überschrieben, wird die absolute URI aus der Basis-URI und den relativen URIs ermittelt.
type: docs
weight: 27
url: /de/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) Methode

When overridden in a derived class, resolves the absolute URI from the base and relative URIs.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Die Basis-URI, die verwendet wird, um die relative URI aufzulösen. |
| relativeUri | [String](../../../system/string/) | Die aufzulösende URI. Die URI kann absolut oder relativ sein. Ist sie absolut, ersetzt dieser Wert effektiv den **baseUri**-Wert. Ist sie relativ, wird sie mit dem **baseUri** kombiniert, um eine absolute URI zu erzeugen. |

### Rückgabewert

Die absolute URI oder **nullptr**, wenn die relative URI nicht aufgelöst werden kann.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [XmlResolver](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)