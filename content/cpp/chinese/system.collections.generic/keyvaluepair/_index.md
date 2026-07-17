---
title: KeyValuePair
second_title: Aspose.Slides C++ API 参考
description: "键和值的配对。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 378
url: /zh/system.collections.generic/keyvaluepair/
---
## KeyValuePair 类

键和值的配对。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../../system/smartptr/) 类来管理此类型的对象。

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## 方法

| Method | Description |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | 获取键。 |
| const TValue\& [get_Value](./get_value/)() const | 获取值。 |
| int [GetHashCode](./gethashcode/)() const | 通过对键的哈希和值的哈希进行异或来计算键值对的哈希。 |
| **bool** [IsNull](./isnull/)() const | 始终返回 false。 |
|  [KeyValuePair](./keyvaluepair/)() | 空键值对初始化器。 |
|  [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | 构造函数。 |
|  [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | 类型转换构造函数。 |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | 用于从 IComparer<KeyValuePair<TKey, TValue>> 继承的类的补丁，不进行任何比较。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 将键值对转换为字符串。 |

## 另请参见

* 命名空间 [System::Collections::Generic](../)
* 库 [Aspose.Slides](../../)