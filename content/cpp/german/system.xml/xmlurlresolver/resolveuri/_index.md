---
title: ResolveUri()
second_title: Aspose.Slides für C++ API Referenz
description: Löst die absolute URI aus der Basis-URI und den relativen URIs.
type: docs
weight: 66
url: /de/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) Methode

Löst die absolute URI aus der Basis-URI und der relativen URI.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Die Basis-URI, die zum Auflösen der relativen URI verwendet wird. |
| relativeUri | [String](../../../system/string/) | Die zu auflösende URI. Die URI kann absolut oder relativ sein. Wenn sie absolut ist, ersetzt dieser Wert effektiv den **baseUri**-Wert. Wenn sie relativ ist, wird sie mit dem **baseUri** kombiniert, um eine absolute URI zu erzeugen. |

### Rückgabewert

Die absolute URI oder **nullptr**, falls die relative URI nicht aufgelöst werden kann.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [XmlUrlResolver](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)