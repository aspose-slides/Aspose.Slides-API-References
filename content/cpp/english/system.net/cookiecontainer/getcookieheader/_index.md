---
title: GetCookieHeader()
second_title: Aspose.Slides for C++ API Reference
description: Return an HTTP header that contains cookies associated with the specified URI.
type: docs
weight: 170
url: /system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) method


Return an HTTP header that contains cookies associated with the specified URI.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | An URI for which header name will be built. |

### Return Value

An HTTP header that contains cookies associated with the specified URI.

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) method


Return an HTTP header that contains cookies associated with the specified URI.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | An URI for which header name will be built. |
| optCookie2 | [String](../../../system/string/)\& | The output parameter where a cookie with the maximum supported version will be assigned. |

### Return Value

An HTTP header that contains cookies associated with the specified URI.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Uri](../../../system/uri/)
* Class [CookieContainer](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)