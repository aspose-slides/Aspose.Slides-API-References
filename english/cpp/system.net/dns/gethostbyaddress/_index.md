---
title: GetHostByAddress()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new IPHostEntry-class instance using the specified string representation of an IP address.
type: docs
weight: 14
url: /cpp/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) method


Creates a new IPHostEntry-class instance using the specified string representation of an IP address.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| address | [String](../../../system/string/) | The string representation of an IP address. |

### Return Value

A newly created IPHostEntry-class instance.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) method


Creates a new IPHostEntry-class instance using the specified IP address.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | The IP address. |

### Return Value

A newly created IPHostEntry-class instance.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [String](../../../system/string/)
* Class [Dns](../)
* Class [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)