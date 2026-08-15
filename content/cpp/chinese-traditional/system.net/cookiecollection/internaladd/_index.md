---
title: InternalAdd()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的 cookie 新增至集合中。
type: docs
weight: 118
url: /zh-hant/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) 方法


將指定的 cookie 新增至集合中。

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | 要新增的 cookie。 |
| isStrict | **bool** | True 當指定的 cookie 必須取代舊的時候，否則為 false。 |

### 傳回值

當指定的 cookie 取代舊的時，傳回 0，否則傳回 1。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Cookie](../../cookie/)
* 類別 [CookieCollection](../)
* 命名空間 [System::Net](../../)
* Library [Aspose.Slides](../../../)