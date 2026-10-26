---
title: ResolveUri()
second_title: Aspose.Slides für C++ API-Referenz
description: Löst die absolute URI aus der Basis- und relativen URI, indem ResolveUri auf dem zugrunde liegenden XmlResolver aufgerufen wird.
type: docs
weight: 40
url: /de/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) Methode

Löst die absolute URI aus der Basis- und relativen URI, indem **ResolveUri** auf dem zugrunde liegenden [XmlResolver](../../xmlresolver/) aufgerufen wird.

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Die Basis-URI, die zum Auflösen der relativen URI verwendet wird. |
| relativeUri | [String](../../../system/string/) | Die zu auflösende URI. Die URI kann absolut oder relativ sein. Wenn sie absolut ist, ersetzt dieser Wert effektiv den **baseUri**-Wert. Wenn sie relativ ist, wird sie mit dem **baseUri** kombiniert, um eine absolute URI zu erzeugen. |

### Rückgabewert

Die absolute URI oder **nullptr**, falls die relative URI nicht aufgelöst werden kann (zurückgegeben durch Aufruf von **ResolveUri** auf dem zugrunde liegenden [XmlResolver](../../xmlresolver/)).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [XmlSecureResolver](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)