---
title: GetCookieHeader()
second_title: Aspose.Slides for C++ API 參考
description: 傳回一個包含與指定 URI 相關聯之 Cookie 的 HTTP 標頭。
type: docs
weight: 170
url: /zh-hant/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) method


傳回一個包含與指定 URI 相關聯之 Cookie 的 HTTP 標頭。

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 為其建構標頭名稱的 URI。 |

### 傳回值

傳回一個包含與指定 URI 相關聯之 Cookie 的 HTTP 標頭。

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) method


傳回一個包含與指定 URI 相關聯之 Cookie 的 HTTP 標頭。

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 為其建構標頭名稱的 URI。 |
| optCookie2 | [String](../../../system/string/)\& | 輸出參數，將指派具有最高支援版本的 Cookie。 |

### 傳回值

傳回一個包含與指定 URI 相關聯之 Cookie 的 HTTP 標頭。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Uri](../../../system/uri/)
* Class [CookieContainer](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)