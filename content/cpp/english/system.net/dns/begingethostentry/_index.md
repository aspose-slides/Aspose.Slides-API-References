---
title: BeginGetHostEntry()
second_title: Aspose.Slides for C++ API Reference
description: Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified string that contains a host name or IP address.
type: docs
weight: 105
url: /system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) method


Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified string that contains a host name or IP address.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | The string that contains a hostname or IP address. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | A callback to be called when the operation completes. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | User-provided data used to uniquely identify each asynchronous operation. |

### Return Value

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous operation.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) method


Initiates an asynchronous operation to create a new IPHostEntry-class instance using the specified IP address.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | The IP address. |
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
* Class [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)