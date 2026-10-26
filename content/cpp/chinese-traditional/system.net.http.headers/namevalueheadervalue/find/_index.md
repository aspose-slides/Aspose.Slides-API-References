---
title: Find()
second_title: Aspose.Slides for C++ API 參考
description: 根據指定的名稱，在集合中尋找 NameValueHeaderValue 類別的實例。
type: docs
weight: 144
url: /zh-hant/system.net.http.headers/namevalueheadervalue/find/
---
## NameValueHeaderValue::Find(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, String) 方法

依據指定的名稱，在集合中尋找 NameValueHeaderValue 類別實例。

```cpp
static System::SharedPtr<NameValueHeaderValue> System::Net::Http::Headers::NameValueHeaderValue::Find(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, String name)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue 類別實例的集合。 |
| name | [String](../../../system/string/) | 要搜尋的名稱。 |

### 返回值

在找到時返回 NameValueHeaderValue 類別實例，否則返回 nullptr。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [NameValueHeaderValue](../)
* 類別 [ObjectCollection](../../objectcollection/)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Net::Http::Headers](../../)
* 函式庫 [Aspose.Slides](../../../)