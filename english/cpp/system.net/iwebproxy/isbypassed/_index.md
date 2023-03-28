---
title: IsBypassed()
second_title: Aspose.Slides for C++ API Reference
description: Returns a value that indicates if the proxy must not be used for the specified host.
type: docs
weight: 40
url: /cpp/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed([System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>) method


Returns a value that indicates if the proxy must not be used for the specified host.

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The host URI to check. |

### Return Value

True when the proxy server must not be used, otherwise false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [IWebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
