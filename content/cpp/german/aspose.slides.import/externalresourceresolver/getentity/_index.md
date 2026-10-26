---
title: GetEntity()
second_title: Aspose.Slides für C++ API Referenz
description: Ordnet eine URI einem Objekt zu, das die eigentliche Ressource enthält.
type: docs
weight: 14
url: /de/aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) Methode


Ordnet eine URI einem Objekt zu, das die eigentliche Ressource enthält.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Absolute URI zum Objekt. |

### Rückgabewert

Ein [System::IO::Stream](../../../system.io/stream/)-Objekt oder null, wenn die Ressource nicht gestreamt werden kann.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [String](../../../system/string/)
* Klasse [ExternalResourceResolver](../)
* Namensraum [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)