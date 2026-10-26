---
title: TransformBlock()
second_title: Aspose.Slides C++ API 参考
description: 处理数据块并将数据复制到输出数组。
type: docs
weight: 53
url: /zh/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) method

处理数据块并将数据复制到输出数组。

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/)用于读取数据。 |
| inputOffset | **int32_t** | 输入缓冲区偏移。 |
| inputCount | **int32_t** | 要处理的字节数。 |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 输出缓冲区，用于复制数据；如果为 nullptr 则不进行复制。 |
| outputOffset | **int32_t** | 输出缓冲区偏移。 |

### 返回值

已写入的字节数。

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [ToBase64Transform](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)