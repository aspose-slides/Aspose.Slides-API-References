---
title: BeginGetHostAddresses()
second_title: Aspose.Slides for C++ API Reference
description: Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified string that contains a host name or IP address.
type: docs
weight: 131
url: /cpp/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses([String](../../../system/string/), [AsyncCallback](../../../system/asynccallback/), [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>) method


Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified string that contains a host name or IP address.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | A string that contains a hostname or IP address. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | A callback to be called when the operation completes. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | User-provided data used to uniquely identify each asynchronous operation. |

### Return Value

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous operation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
