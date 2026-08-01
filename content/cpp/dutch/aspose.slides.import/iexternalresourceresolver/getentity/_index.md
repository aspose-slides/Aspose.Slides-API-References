---
title: GetEntity()
second_title: Aspose.Slides voor C++ API Referentie
description: Koppelt een URI aan een object dat de daadwerkelijke bron bevat.
type: docs
weight: 14
url: /nl/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) methode

Koppelt een URI aan een object dat de daadwerkelijke bron bevat.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Absolute URI naar het object. |

### Retourwaarde

Een [System::IO::Stream](../../../system.io/stream/) object of null als de bron niet kan worden gestreamd.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [String](../../../system/string/)
* Klasse [IExternalResourceResolver](../)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)