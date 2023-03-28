---
title: CreateHttp()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new instance of the WebRequest class using the specified URI.
type: docs
weight: 79
url: /cpp/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp([String](../../../system/string/)) method


Creates a new instance of the [WebRequest](../) class using the specified URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | The URI that is used to create a new instance of the [WebRequest](../) class. |

### Return Value

A newly created WebRequest-class instance.
## Remarks



NotSupportedException will be thrown when the specified URI begins with any scheme except for [http://](http://) or [https://](https://). 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpWebRequest](../../httpwebrequest/)
* Class [String](../../../system/string/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
## WebRequest::CreateHttp([System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>) method


Creates a new instance of the [WebRequest](../) class using the specified URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The URI that is used to create a new instance of the [WebRequest](../) class. |

### Return Value

A newly created WebRequest-class instance.
## Remarks



NotSupportedException will be thrown when the specified URI begins with any scheme except for [http://](http://) or [https://](https://). 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpWebRequest](../../httpwebrequest/)
* Class [Uri](../../../system/uri/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
