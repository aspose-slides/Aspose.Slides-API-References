---
title: InternalAdd()
second_title: Aspose.Slides for C++ API Reference
description: Adds the specified cookie to the collection.
type: docs
weight: 118
url: /system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) method


Adds the specified cookie to the collection.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | The cookie to add. |
| isStrict | **bool** | True when the specified cookie must replace the old one, otherwise false. |

### Return Value

0 when the specified cookie replaced the old one, otherwise 1.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieCollection](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)