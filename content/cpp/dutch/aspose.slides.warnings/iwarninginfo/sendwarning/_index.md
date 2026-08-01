---
title: SendWarning()
second_title: Aspose.Slides voor C++ API-referentie
description: Als receiver niet null is, beëindigt de waarschuwing naar een opgegeven receiver en werpt de AbortRequestedException als receiver heeft besloten de bewerking af te breken.
type: docs
weight: 27
url: /nl/aspose.slides.warnings/iwarninginfo/sendwarning/
---
## IWarningInfo::SendWarning(System::SharedPtr\<IWarningCallback\>) methode

Als receiver niet null is, stopt de waarschuwing naar een opgegeven receiver en werpt de AbortRequestedException als receiver heeft besloten de bewerking af te breken.

```cpp
virtual void Aspose::Slides::Warnings::IWarningInfo::SendWarning(System::SharedPtr<IWarningCallback> receiver)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| receiver | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningCallback](../../iwarningcallback/)\> | Receiver-object [IWarningCallback](../../iwarningcallback/) |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningCallback](../../iwarningcallback/)
* Class [IWarningInfo](../)
* Namespace [Aspose::Slides::Warnings](../../)
* Library [Aspose.Slides](../../../)