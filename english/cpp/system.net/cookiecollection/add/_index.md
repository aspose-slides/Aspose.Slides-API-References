---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds a cookie to the collection.
type: docs
weight: 53
url: /cpp/system.net/cookiecollection/add/
---
## CookieCollection::Add(const System::SharedPtr\<Cookie\>\&) method


Adds a cookie to the collection.

```cpp
void System::Net::CookieCollection::Add(const System::SharedPtr<Cookie> &cookie) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cookie | const [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\>\& | The cookie to add. |

## CookieCollection::Add(System::SharedPtr\<CookieCollection\>) method


Adds cookies from the specified collection to the current one.

```cpp
void System::Net::CookieCollection::Add(System::SharedPtr<CookieCollection> cookies)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../)\> | The collection from which cookies will be copied to the current one. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieCollection](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)