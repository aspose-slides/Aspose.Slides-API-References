---
title: CancellationToken
second_title: Aspose.Slides for C++ API Reference
description: Propagates notification that operations should be canceled. This class provides a mechanism for cooperative cancellation between threads, allowing one thread to notify others that an operation should be canceled.
type: docs
weight: 14
url: /system.threading/cancellationtoken/
---
## CancellationToken class


Propagates notification that operations should be canceled. This class provides a mechanism for cooperative cancellation between threads, allowing one thread to notify others that an operation should be canceled.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Methods

| Method | Description |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | Default constructor. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | Gets whether this token is capable of being in the canceled state. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Gets whether cancellation has been requested for this token. |
| static [CancellationToken](./) [get_None](./get_none/)() | Returns an empty [System::Threading::CancellationToken](./) value. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | Registers a callback that will be invoked when cancellation is requested. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Throws a OperationCanceledException if cancellation has been requested. |
## Remarks



A [CancellationToken](./) can only be canceled through its associated [CancellationTokenSource](../cancellationtokensource/). 

## See Also

* Namespace [System::Threading](../)
* Library [Aspose.Slides](../../)