---
title: ResolveUri()
second_title: Aspose.Slides för C++ API-referens
description: Löser den absoluta URI:n från bas- och relativa URI:er.
type: docs
weight: 1
url: /sv/aspose.slides.import/iexternalresourceresolver/resolveuri/
---
## IExternalResourceResolver::ResolveUri(System::String, System::String) metod

Löser den absoluta URI:n från den bas- och relativa URI:n.

```cpp
virtual System::String Aspose::Slides::Import::IExternalResourceResolver::ResolveUri(System::String baseUri, System::String relativeUri)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | Bas-URI för länkande objekt |
| relativeUri | [System::String](../../../system/string/) | Relativ URI till det länkade objektet. |

### Returvärde

Absolut URI eller null om den relativa URI:n inte kan lösas.

## Se även

* Klass [String](../../../system/string/)
* Klass [IExternalResourceResolver](../)
* Namnrymd [Aspose::Slides::Import](../../)
* Bibliotek [Aspose.Slides](../../../)