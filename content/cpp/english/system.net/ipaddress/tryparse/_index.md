---
title: TryParse()
second_title: Aspose.Slides for C++ API Reference
description: Tries to convert a passed string to an instance of the IPAddress class.
type: docs
weight: 222
url: /system.net/ipaddress/tryparse/
---
## IPAddress::TryParse(String, System::SharedPtr\<IPAddress\>\&) method


Tries to convert a passed string to an instance of the [IPAddress](../) class.

```cpp
static bool System::Net::IPAddress::TryParse(String ipString, System::SharedPtr<IPAddress> &address)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ipString | [String](../../../system/string/) | A string to parse. |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../)\>\& | An instance where a parsed object will be assigned. |

### Return Value

True when the parsing is successfully done, otherwise false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IPAddress](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)