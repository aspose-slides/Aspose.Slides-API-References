---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides for C++ API Reference
description: Creates a linked token source that cancels when any of the provided tokens cancel.
type: docs
weight: 66
url: /system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) method


Creates a linked token source that cancels when any of the provided tokens cancel.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | First cancellation token to monitor. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | Second cancellation token to monitor. |

### Return Value

New token source that will cancel when either input token cancels.
## Remarks



The returned source will immediately cancel if either input token is already canceled. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CancellationTokenSource](../)
* Class [CancellationToken](../../cancellationtoken/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)