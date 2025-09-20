---
title: get_CanBeCanceled()
second_title: Aspose.Slides for C++ API Reference
description: Gets whether this token is capable of being in the canceled state.
type: docs
weight: 27
url: /system.threading/cancellationtoken/get_canbecanceled/
---
## CancellationToken::get_CanBeCanceled() const method


Gets whether this token is capable of being in the canceled state.

```cpp
bool System::Threading::CancellationToken::get_CanBeCanceled() const
```


### Return Value

true if this token is capable of being in the canceled state; otherwise, false.
## Remarks



Tokens created from [CancellationTokenSource](../../cancellationtokensource/) will return true, while the None token will always return false. 

## See Also

* Class [CancellationToken](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)