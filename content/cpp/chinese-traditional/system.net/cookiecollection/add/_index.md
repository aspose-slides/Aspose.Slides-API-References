---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 將 Cookie 加入集合。
type: docs
weight: 53
url: /zh-hant/system.net/cookiecollection/add/
---
## CookieCollection::Add(const System::SharedPtr\<Cookie\>\&) 方法

將 Cookie 加入集合。

```cpp
void System::Net::CookieCollection::Add(const System::SharedPtr<Cookie> &cookie) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cookie | const [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\>\& | 要加入的 Cookie。 |

## CookieCollection::Add(System::SharedPtr\<CookieCollection\>) 方法

將指定集合中的 Cookie 加入目前的集合。

```cpp
void System::Net::CookieCollection::Add(System::SharedPtr<CookieCollection> cookies)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../)\> | 將從此集合複製 Cookie 到目前的集合。 |

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Cookie](../../cookie/)
* 類別 [CookieCollection](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)