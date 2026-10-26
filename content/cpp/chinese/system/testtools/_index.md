---
title: TestTools
second_title: Aspose.Slides for C++ API 参考
description: 提供一组有用的方法，用于检查不同类型和函数的一些基本属性。
type: docs
weight: 1899
url: /zh/system/testtools/
---
## TestTools 结构体

提供一组有用的方法，用于检查不同类型和函数的一些基本属性。

```cpp
class TestTools
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | 检查函数是否抛出任何类型的异常。 |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | 检查字符串是否为空。 |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 检查集合是否为空。 |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | 检查特定值是否为 null。[Version](../version/) 用于算术和枚举类型。 |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | 检查特定值是否为 null。[Version](../version/) 用于非算术和非枚举值类型。 |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 检查特定值是否为 null。[Version](../version/) 用于非算术值类型。 |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | 检查特定值是否为 null。[Version](../version/) 用于键值对。 |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | 检查字符串是否为 null。 |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 检查集合是否为 null 或为空。 |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | 检查字符串是否为 null 或为空。 |
## 参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)