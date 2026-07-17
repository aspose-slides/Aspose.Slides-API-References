---
title: CopyTo()
second_title: Aspose.Slides C++ API 参考
description: 将字符串字符复制到现有数组元素中。不进行大小调整。
type: docs
weight: 430
url: /zh/system/string/copyto/
---
## String::CopyTo(int, const ArrayPtr\<char_t\>\&, int, int) const 方法

将字符串字符复制到现有数组元素中。不会进行大小调整。

```cpp
void System::String::CopyTo(int sourceIndex, const ArrayPtr<char_t> &destination, int destinationIndex, int count) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceIndex | int | 字符串中开始读取的索引。 |
| destination | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 目标数组。 |
| destinationIndex | int | 数组中开始写入的索引。 |
| count | int | 要复制的字符数。 |

## 另见

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)