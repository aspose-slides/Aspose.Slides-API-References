---
title: TransformFinalBlock()
second_title: Aspose.Slides for C++ API 参考
description: 处理最后一个数据块并计算输出值。
type: docs
weight: 14
url: /zh/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) 方法


处理数据的最后一个块并计算输出值。

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用于读取数据。 |
| inputOffset | int | 输入缓冲区偏移量。 |
| inputCount | int | 要处理的字节数。 |

### 返回值

为整个输入序列计算的输出。

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [ICryptoTransform](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)