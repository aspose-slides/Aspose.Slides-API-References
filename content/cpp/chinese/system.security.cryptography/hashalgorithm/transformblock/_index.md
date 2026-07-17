---
title: TransformBlock()
second_title: Aspose.Slides for C++ API 参考
description: 处理数据块并将数据复制到输出数组。
type: docs
weight: 66
url: /zh/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) 方法

处理数据块并将数据复制到输出数组。

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用于读取数据。 |
| inputOffset | int | 输入缓冲区偏移。 |
| inputCount | int | 要处理的字节数。 |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 用于复制数据的输出缓冲区；nullptr 表示不进行复制。 |
| outputOffset | int | 输出缓冲区偏移。 |

### 返回值

已写入的字节数。

## 另请参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [HashAlgorithm](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)