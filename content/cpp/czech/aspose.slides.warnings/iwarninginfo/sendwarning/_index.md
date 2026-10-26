---
title: SendWarning()
second_title: Aspose.Slides pro C++ – reference API
description: Pokud není receiver null, ukončí varování pro určený receiver a vyhodí výjimku AbortRequestedException, pokud receiver rozhodne o přerušení operace.
type: docs
weight: 27
url: /cs/aspose.slides.warnings/iwarninginfo/sendwarning/
---
## IWarningInfo::SendWarning(System::SharedPtr\<IWarningCallback\>) metoda

Pokud receiver není null, ukončí varování na určený receiver a vyhodí výjimku AbortRequestedException, pokud receiver rozhodne o přerušení operace.

```cpp
virtual void Aspose::Slides::Warnings::IWarningInfo::SendWarning(System::SharedPtr<IWarningCallback> receiver)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| receiver | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningCallback](../../iwarningcallback/)\> | objekt Receiver [IWarningCallback](../../iwarningcallback/) |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IWarningCallback](../../iwarningcallback/)
* Třída [IWarningInfo](../)
* Jmenný prostor [Aspose::Slides::Warnings](../../)
* Knihovna [Aspose.Slides](../../../)