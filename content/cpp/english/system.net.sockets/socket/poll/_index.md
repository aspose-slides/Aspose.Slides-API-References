---
title: Poll()
second_title: Aspose.Slides for C++ API Reference
description: Returns the status of the socket based on the specified polling mode.
type: docs
weight: 742
url: /system.net.sockets/socket/poll/
---
## Socket::Poll(int32_t, SelectMode) method


Returns the status of the socket based on the specified polling mode.

```cpp
bool System::Net::Sockets::Socket::Poll(int32_t microSeconds, SelectMode mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| microSeconds | **int32_t** | The amount of time in milliseconds to wait for a response. |
| mode | [SelectMode](../../selectmode/) | The polling mode. |

### Return Value

The status of the socket based on the specified polling mode.

## See Also

* Enum [SelectMode](../../selectmode/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)