---
title: set_InterruptionToken()
second_title: Aspose.Slides for C++ API Reference
description: The token to monitor for interruption requests.
type: docs
weight: 248
url: /aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) method


The token to monitor for interruption requests.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## Remarks


This token manages the whole [IPresentation](../../ipresentation/) instance lifetime. Any long-running operation, such as presentaion loading or saving, will be interrupted via calling of the [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) method of the [IInterruptionTokenSource](../../iinterruptiontokensource/). 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IInterruptionToken](../../iinterruptiontoken/)
* Class [ILoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)