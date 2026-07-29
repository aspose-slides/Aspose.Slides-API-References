---
title: GetEntity()
second_title: Aspose.Slides för C++ API-referens
description: Mappar en URI till ett objekt som innehåller den faktiska resursen.
type: docs
weight: 14
url: /sv/aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) metod


Mappar en URI till ett objekt som innehåller den faktiska resursen.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | Absolut URI till objektet. |

### Returvärde

Ett [System::IO::Stream](../../../system.io/stream/)-objekt eller null om resursen inte kan strömmas.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Stream](../../../system.io/stream/)
* Klass [String](../../../system/string/)
* Klass [ExternalResourceResolver](../)
* Namnrymd [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)