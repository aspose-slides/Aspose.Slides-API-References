---
title: SendWarning()
second_title: Aspose.Slides för C++ API-referens
description: Om mottagaren inte är null avslutar varningen till en specificerad mottagare och kastar AbortRequestedException om mottagaren bestämde sig för att avbryta en operation.
type: docs
weight: 27
url: /sv/aspose.slides.warnings/iwarninginfo/sendwarning/
---
## IWarningInfo::SendWarning(System::SharedPtr\<IWarningCallback\>) metod


Om mottagaren inte är null avslutas varningen till en specificerad mottagare och ett AbortRequestedException kastas om mottagaren bestämde sig för att avbryta en operation.

```cpp
virtual void Aspose::Slides::Warnings::IWarningInfo::SendWarning(System::SharedPtr<IWarningCallback> receiver)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| receiver | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningCallback](../../iwarningcallback/)\> | Mottagarobjekt [IWarningCallback](../../iwarningcallback/) |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IWarningCallback](../../iwarningcallback/)
* Klass [IWarningInfo](../)
* Namnrymd [Aspose::Slides::Warnings](../../)
* Bibliotek [Aspose.Slides](../../../)