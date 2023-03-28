---
title: set_InterruptionToken()
second_title: Aspose.Slides for C++ API Reference
description: The token to monitor for interruption requests.
type: docs
weight: 248
url: /cpp/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken([System::SharedPtr](../../../system/sharedptr/)\<[IInterruptionToken](../../iinterruptiontoken/)\>) method


The token to monitor for interruption requests.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## Remarks


This token manages the whole [IPresentation](../../ipresentation/) instance lifetime. Any long-running operation, such as loading or saving of presentation, will be interrupted via calling of the [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) method of the [InterruptionTokenSource](../../interruptiontokensource/). 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IInterruptionToken](../../iinterruptiontoken/)
* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
