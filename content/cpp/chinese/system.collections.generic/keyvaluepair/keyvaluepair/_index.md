---
title: KeyValuePair()
second_title: Aspose.Slides C++ API 参考
description: 空键值对初始化器。
type: docs
weight: 1
url: /zh/system.collections.generic/keyvaluepair/keyvaluepair/
---
## KeyValuePair::KeyValuePair() 构造函数

空键值对初始化器。

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair()
```

## KeyValuePair::KeyValuePair(const TKey\&, const TValue\&) 构造函数

构造函数。

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const TKey &key, const TValue &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | const TKey\& | 键。 |
| value | const TValue\& | 值。 |

## KeyValuePair::KeyValuePair(const std::pair\<OtherK, OtherV\>\&) 构造函数

类型转换构造函数。

```cpp
template<typename OtherK,typename OtherV> System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const std::pair<OtherK, OtherV> &pair)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| OtherK | 其他键类型。 |
| OtherV | 其他值类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pair | const std::pair\<OtherK, OtherV\>\& | 对值。 |

## 另请参见

* 类 [KeyValuePair](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)