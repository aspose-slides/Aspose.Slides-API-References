---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds a cookie to the collection.
type: docs
weight: 105
url: /cpp/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) method


Adds a cookie to the collection.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | The cookie to add. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) method


Adds a cookie to the collection.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | The cookie to add. |
| throwOnError | **bool** | A value that indicates if an exception will be thrown when an error occurs. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) method


Copies cookies from the specified collection to the current one.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | The collection from which cookies will be copied. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) method


Adds a cookie for the specified URI.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | An URI of the cookie. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | The cookie to add. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) method


Copies cookies from the specified collection for the specified URI to the current collection.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | An URI of the cookie. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | A cookie collection from which cookies must be copied. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieContainer](../)
* Class [CookieCollection](../../cookiecollection/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)