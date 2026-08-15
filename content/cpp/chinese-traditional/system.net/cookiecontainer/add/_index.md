---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 將 cookie 加入集合。
type: docs
weight: 105
url: /zh-hant/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) 方法


將 cookie 加入集合。

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | 要加入的 cookie。 |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) 方法


將 cookie 加入集合。

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | 要加入的 cookie。 |
| throwOnError | **bool** | 指示發生錯誤時是否拋出例外的值。 |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) 方法


將指定集合中的 cookies 複製到目前的集合。

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | 要從中複製 cookies 的集合。 |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) 方法


為指定的 URI 加入 cookie。

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | cookie 的 URI。 |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | 要加入的 cookie。 |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) 方法


將指定集合中屬於指定 URI 的 cookies 複製到目前的集合。

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | cookie 的 URI。 |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | 必須從中複製 cookies 的集合。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieContainer](../)
* Class [CookieCollection](../../cookiecollection/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)