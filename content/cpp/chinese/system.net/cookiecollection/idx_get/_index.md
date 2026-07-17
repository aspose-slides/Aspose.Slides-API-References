---
title: idx_get()
second_title: Aspose.Slides for C++ API 参考
description: 返回 Cookie 集合中指定索引处的 Cookie。
type: docs
weight: 40
url: /zh/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) 方法

返回 Cookie 集合中指定索引处的 Cookie。

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| index | **int32_t** | 必须返回的 Cookie 的索引。 |

### 返回值

指定索引处的 Cookie。

## CookieCollection::idx_get(String) 方法

返回 Cookie 集合中指定名称的 Cookie。

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 必须返回的 Cookie 的名称。 |

### 返回值

当找到时，返回 Cookie 集合中指定名称的 Cookie；否则返回 nullptr。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Cookie](../../cookie/)
* 类 [CookieCollection](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)