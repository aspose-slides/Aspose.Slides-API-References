---
title: GetHostEntry()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new IPHostEntry-class instance using the specified string that contains a host name or IP address.
type: docs
weight: 79
url: /cpp/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) method


Creates a new IPHostEntry-class instance using the specified string that contains a host name or IP address.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | A string that contains a hostname or IP address. |

### Return Value

A newly created IPHostEntry-class instance.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) method


Creates a new IPHostEntry-class instance using the specified IP address.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
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