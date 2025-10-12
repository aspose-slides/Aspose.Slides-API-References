---
title: Cancel()
second_title: Aspose.Slides for C++ API Reference
description: Communicates a request for cancellation.
type: docs
weight: 40
url: /system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() method


Communicates a request for cancellation.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## Remarks



All registered callbacks will be invoked. 

Subsequent calls to [get_IsCancellationRequested()](../get_iscancellationrequested/) will return true. 

Callbacks are executed synchronously during this call. 

## See Also

* Class [CancellationTokenSource](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)