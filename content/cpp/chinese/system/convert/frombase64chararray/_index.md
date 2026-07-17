---
title: FromBase64CharArray()
second_title: Aspose.Slides for C++ API 参考
description: 将表示为 Unicode 字符数组中范围的 base-64 编码数据解码。
type: docs
weight: 53
url: /zh/system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) 方法

将表示为 Unicode 字符数组中范围的 base-64 编码数据解码。

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 包含要解码的数据的数组 |
| offset | int | 输入数组中解码范围开始的位置 |
| length | int | 要解码的范围的长度 |

### 返回值

包含解码后数据的字节数组

## 另请参见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 结构体 [Convert](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)