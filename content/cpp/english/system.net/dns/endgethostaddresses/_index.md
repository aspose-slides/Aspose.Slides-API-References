---
title: EndGetHostAddresses()
second_title: Aspose.Slides for C++ API Reference
description: Waits until the specified asynchronous operation to create a new IPHostEntry-class instance completes.
type: docs
weight: 144
url: /system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) method


Waits until the specified asynchronous operation to create a new IPHostEntry-class instance completes.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous operation. |

### Return Value

A newly created IPHostEntry-class instance.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPAddress](../../ipaddress/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)