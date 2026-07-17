---
title: operator==()
second_title: Aspose.Slides for C++ API 参考
description: 使用 'equals' 语义比较两个键值对。对键和值均使用 operator == 或 EqualsTo 方法（以已定义的为准）。
type: docs
weight: 690
url: /zh/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) 函数

比较两个键值对，使用‘equals’语义。对于键和值，使用 operator == 或 EqualsTo 方法（取决于哪一个已定义）。

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TKey | 键类型。 |
| TValue | 值类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | 左操作数。 |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | 右操作数。 |

### 返回值

如果键和值都匹配则返回 true，否则返回 false。

## 另见

* 类 [KeyValuePair](../keyvaluepair/)
* 命名空间 [System::Collections::Generic](../)
* 库 [Aspose.Slides](../../)