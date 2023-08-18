---
title: RegisterPrefix()
second_title: Aspose.Slides for C++ API Reference
description: Registers the WebRequest descendant for the specified URI.
type: docs
weight: 92
url: /system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) method


Registers the [WebRequest](../) descendant for the specified URI.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | The URI or the URI prefix. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | Creates new instances of the [WebRequest](../) class. |

### Return Value

True when the [WebRequest](../) descendant is successfully registered for the specified URI, otherwise false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IWebRequestCreate](../../iwebrequestcreate/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)