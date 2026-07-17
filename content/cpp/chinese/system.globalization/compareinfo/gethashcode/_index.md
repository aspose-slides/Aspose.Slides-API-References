---
title: GetHashCode()
second_title: Aspose.Slides for C++ API 参考
description: 基于指定的比较选项获取字符串哈希码。
type: docs
weight: 144
url: /zh/system.globalization/compareinfo/gethashcode/
---
## CompareInfo::GetHashCode(const String\&, CompareOptions) const 方法


获取基于指定比较选项的字符串哈希码。

```cpp
virtual int System::Globalization::CompareInfo::GetHashCode(const String &value, CompareOptions options) const
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 输入字符串。 |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 比较选项。 |

### 返回值

哈希码。

## CompareInfo::GetHashCode() const 方法


相当于 C# [Object.GetHashCode()](../../../system/object/gethashcode/) 方法。启用自定义对象的散列。

```cpp
int System::Globalization::CompareInfo::GetHashCode() const override
```


### 返回值

哈希码值，由相应的类计算。

## 另请参阅

* 枚举 [CompareOptions](../../compareoptions/)
* 类 [String](../../../system/string/)
* 类 [CompareInfo](../)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)