---
title: GetEntity()
second_title: Aspose.Slides für C++ API-Referenz
description: Ordnet einen URI einem Objekt zu, das die eigentliche Ressource enthält.
type: docs
weight: 14
url: /de/aspose.slides.import/htmlexternalresolver/getentity/
---
## HtmlExternalResolver::GetEntity(System::String) Methode

Ordnet einen URI einem Objekt zu, das die eigentliche Ressource enthält.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::HtmlExternalResolver::GetEntity(System::String absoluteUri) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Absoluter URI zum Objekt. |

### Rückgabewert

Ein [System::IO::Stream](../../../system.io/stream/) Objekt oder null, wenn die Ressource nicht gestreamt werden kann.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [String](../../../system/string/)
* Klasse [HtmlExternalResolver](../)
* Namensraum [Aspose::Slides::Import](../../)
* Bibliothek [Aspose.Slides](../../../)