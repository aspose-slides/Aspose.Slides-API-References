---
title: BeginResolve()
second_title: Aspose.Slides for C++ API Reference
description: Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified host name.
type: docs
weight: 157
url: /system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) method


Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified host name.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | A host name that is used to create a new instance of the [IPHostEntry](../../iphostentry/) class. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | A callback to be called when the operation completes. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | User-provided data used to uniquely identify each asynchronous operation. |

### Return Value

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous operation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)