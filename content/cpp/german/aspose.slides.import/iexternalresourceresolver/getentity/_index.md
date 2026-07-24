---
title: GetEntity()
second_title: Aspose.Slides für C++ API-Referenz
description: Ordnet einen URI einem Objekt zu, das die tatsächliche Ressource enthält.
type: docs
weight: 14
url: /de/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) Methode

Ordnet einen URI einem Objekt zu, das die tatsächliche Ressource enthält.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Absoluter URI zum Objekt. |

### Rückgabewert

Ein [System::IO::Stream](../../../system.io/stream/) Objekt oder null, falls die Ressource nicht gestreamt werden kann.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)