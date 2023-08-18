---
title: idx_get()
second_title: Aspose.Slides for C++ API Reference
description: Returns a cookie from the cookie collection at the specified index.
type: docs
weight: 40
url: /system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) method


Returns a cookie from the cookie collection at the specified index.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The index of a cookie that must be returned. |

### Return Value

A cookie at the specified index.

## CookieCollection::idx_get(String) method


Returns a cookie from the cookie collection by specified name.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The name of a cookie that must be returned. |

### Return Value

A cookie from the cookie collection by specified name when it is found, otherwise nullptr.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieCollection](../)
* Class [String](../../../system/string/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)