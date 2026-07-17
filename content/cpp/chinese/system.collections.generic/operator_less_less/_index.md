---
title: operator<<()
second_title: Aspose.Slides C++ API 参考
description: 使用 UTF-8 编码将数据插入流中。
type: docs
weight: 716
url: /zh/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream&, const KeyValuePair<TKey, TValue>&) 函数

使用 UTF-8 编码将数据插入流中。

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TKey | Key type. |
| TValue | Value type. |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | std::ostream& | Output stream to insert data to. |
| pair | const [KeyValuePair](../keyvaluepair/)<TKey, TValue>& | [Data](../../system.data/) 用于插入。 |

### 返回值

**stream**。

## System::Collections::Generic::operator<<(std::wostream&, const KeyValuePair<TKey, TValue>&) 函数

将数据插入流中。

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TKey | Key type. |
| TValue | Value type. |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | std::wostream& | Output stream to insert data to. |
| pair | const [KeyValuePair](../keyvaluepair/)<TKey, TValue>& | [Data](../../system.data/) 用于插入。 |

### 返回值

**stream**。

## 另请参见

* 类 [KeyValuePair](../keyvaluepair/)
* 命名空间 [System::Collections::Generic](../)
* 库 [Aspose.Slides](../../)