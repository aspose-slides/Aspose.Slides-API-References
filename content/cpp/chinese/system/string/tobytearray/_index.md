---
title: ToByteArray()
second_title: Aspose.Slides C++ API 参考
description: 将字符串或子字符串转换为字节数组。
type: docs
weight: 508
url: /zh/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const 方法

将字符串或子字符串转换为字节数组。

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | 子字符串的起始索引。 |
| length | **int32_t** | 子字符串的长度。 |
| LE | **bool** | 如果为 true，则使用小端序对字符进行编码；否则，使用大端序。 |

### 返回值

[Array](../../array/) 包含表示字符串字符的字节。

## 参见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类 [String](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)