---
title: Find()
second_title: Aspose.Slides C++ API 参考
description: 在集合中按指定名称查找 NameValueHeaderValue 类实例。
type: docs
weight: 144
url: /zh/system.net.http.headers/namevalueheadervalue/find/
---
## NameValueHeaderValue::Find(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, String) 方法

在集合中按指定名称查找 NameValueHeaderValue 类实例。

```cpp
static System::SharedPtr<NameValueHeaderValue> System::Net::Http::Headers::NameValueHeaderValue::Find(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, String name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue 类实例的集合。 |
| name | [String](../../../system/string/) | 要查找的名称。 |

### 返回值

找到时返回 NameValueHeaderValue 类实例，否则返回 nullptr。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [NameValueHeaderValue](../)
* 类 [ObjectCollection](../../objectcollection/)
* 类 [String](../../../system/string/)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)