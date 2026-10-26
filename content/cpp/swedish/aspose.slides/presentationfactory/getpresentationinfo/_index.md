---
title: GetPresentationInfo()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt PresentationInfo-objekt från fil och binder presentationen till det.
type: docs
weight: 27
url: /sv/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) metod

Skapar ett nytt [PresentationInfo](../../presentationinfo/)-objekt från fil och binder presentationen till det.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/)-fil. |

### Returvärde

[Presentation](../../presentation/)-information bunden till presentationen.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) metod

Skapar ett nytt [PresentationInfo](../../presentationinfo/)-objekt från ström och binder presentationen till det. Hämtar information om presentationen i den specificerade strömmen.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/)-ström. |

### Returvärde

[Presentation](../../presentation/)-information bunden till presentationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPresentationInfo](../../ipresentationinfo/)
* Klass [String](../../../system/string/)
* Klass [PresentationFactory](../)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)