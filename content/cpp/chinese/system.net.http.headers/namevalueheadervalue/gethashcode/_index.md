---
title: GetHashCode()
second_title: Aspose.Slides for C++ API 参考
description: C# Object.GetHashCode() 方法的类似实现。支持对自定义对象进行哈希。
type: docs
weight: 53
url: /zh/system.net.http.headers/namevalueheadervalue/gethashcode/
---
## NameValueHeaderValue::GetHashCode() const 方法

Analog of C# [Object.GetHashCode()](../../../system/object/gethashcode/) 方法. 启用对自定义对象的哈希.

```cpp
int32_t System::Net::Http::Headers::NameValueHeaderValue::GetHashCode() const override
```

### 返回值

由相应类计算的哈希码值。

## NameValueHeaderValue::GetHashCode(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) 方法

返回所有集合项的哈希码。

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetHashCode(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue 类 实例的集合。 |

### 返回值

所有集合项的哈希码。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [NameValueHeaderValue](../)
* 类 [ObjectCollection](../../objectcollection/)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)