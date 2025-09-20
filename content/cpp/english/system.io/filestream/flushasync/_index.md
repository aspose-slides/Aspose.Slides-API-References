---
title: FlushAsync()
second_title: Aspose.Slides for C++ API Reference
description: Asynchronously clears all buffers for this stream, causes any buffered data to be written to the underlying device, and monitors cancellation requests.
type: docs
weight: 157
url: /system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) method


Asynchronously clears all buffers for this stream, causes any buffered data to be written to the underlying device, and monitors cancellation requests.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | The token to monitor for cancellation requests. |

### Return Value

A task that represents the asynchronous flush operation.

## See Also

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)