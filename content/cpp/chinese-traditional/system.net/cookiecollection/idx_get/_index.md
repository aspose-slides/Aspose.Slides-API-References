---
title: idx_get()
second_title: Aspose.Slides for C++ API 參考文件
description: 在指定索引處，從 Cookie 集合返回 Cookie。
type: docs
weight: 40
url: /zh-hant/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) 方法


從 Cookie 集合中返回指定索引的 Cookie。

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 必須返回的 Cookie 的索引。 |

### 返回值

指定索引處的 Cookie。

## CookieCollection::idx_get(String) 方法


從 Cookie 集合中根據指定名稱返回 Cookie。

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 必須返回的 Cookie 名稱。 |

### 返回值

在找到時，根據指定名稱從 Cookie 集合返回 Cookie，否則返回 nullptr。

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Cookie](../../cookie/)
* 類別 [CookieCollection](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)