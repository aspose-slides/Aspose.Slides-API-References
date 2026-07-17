---
title: operator!=()
second_title: Aspose.Slides C++ API 参考
description: 使用反向“等于”语义比较两个键值对。
type: docs
weight: 703
url: /zh/system.collections.generic/operator_not_equal/
---
## System::Collections::Generic::operator!=(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) 函数

使用反向“等于”语义比较两个键值对。

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator!=(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
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

如果键和值都不匹配则为 true，否则为 false。

## 另见

* 类 [KeyValuePair](../keyvaluepair/)
* 命名空间 [System::Collections::Generic](../)
* 库 [Aspose.Slides](../../)