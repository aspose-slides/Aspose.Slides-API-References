---
title: Warning()
second_title: Aspose.Slides for C++ API Reference
description: Callback method which receives warning and decides whether operation should be aborted.
type: docs
weight: 1
url: /cpp/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning([System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\>) method


Callback method which receives warning and decides whether operation should be aborted.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | Warning to process. |

### Return Value

Abortion decision [ReturnAction](../../returnaction/).

## See Also

* Enum [ReturnAction](../../returnaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningInfo](../../iwarninginfo/)
* Class [IWarningCallback](../)
* Namespace [Aspose::Slides::Warnings](../../)
* Library [Aspose.Slides](../../../)
