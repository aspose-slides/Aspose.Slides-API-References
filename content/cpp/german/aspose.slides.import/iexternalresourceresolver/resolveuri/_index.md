---
title: ResolveUri()
second_title: Aspose.Slides für C++ API-Referenz
description: Löst den absoluten URI aus den Basis- und relativen URIs auf.
type: docs
weight: 1
url: /de/aspose.slides.import/iexternalresourceresolver/resolveuri/
---
## IExternalResourceResolver::ResolveUri(System::String, System::String) Methode


Löst den absoluten URI aus den Basis- und relativen URIs auf.

```cpp
virtual System::String Aspose::Slides::Import::IExternalResourceResolver::ResolveUri(System::String baseUri, System::String relativeUri)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | Basis-URI der verlinkenden Objekte |
| relativeUri | [System::String](../../../system/string/) | Relativer URI zum verknüpften Objekt. |

### Rückgabewert

Absoluter URI oder null, wenn der relative URI nicht aufgelöst werden kann.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [IExternalResourceResolver](../)
* Namensraum [Aspose::Slides::Import](../../)
* Bibliothek [Aspose.Slides](../../../)