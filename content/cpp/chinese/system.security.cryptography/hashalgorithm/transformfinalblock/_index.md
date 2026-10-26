---
title: TransformFinalBlock()
second_title: Aspose.Slides C++ API 参考
description: 处理最后的数据块并计算哈希。
type: docs
weight: 79
url: /zh/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) 方法


处理最后的数据块并计算哈希。

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用于读取数据。 |
| inputOffset | int | 输入缓冲区偏移量。 |
| inputCount | int | 要处理的字节数。 |

### 返回值

整个数据序列的哈希。

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [HashAlgorithm](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)