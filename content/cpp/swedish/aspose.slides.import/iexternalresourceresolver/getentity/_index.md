---
title: GetEntity()
second_title: Aspose.Slides för C++ API-referens
description: Mappar en URI till ett objekt som innehåller den faktiska resursen.
type: docs
weight: 14
url: /sv/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) metod

Mappar en URI till ett objekt som innehåller den faktiska resursen.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Absolut URI till objektet. |

### Returvärde

Ett [System::IO::Stream](../../../system.io/stream/)-objekt eller null om resursen inte kan strömmas.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Stream](../../../system.io/stream/)
* Klass [String](../../../system/string/)
* Klass [IExternalResourceResolver](../)
* Namnrymd [Aspose::Slides::Import](../../)
* Bibliotek [Aspose.Slides](../../../)