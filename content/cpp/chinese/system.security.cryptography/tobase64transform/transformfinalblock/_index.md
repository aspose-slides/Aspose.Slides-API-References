---
title: TransformFinalBlock()
second_title: Aspose.Slides for C++ API 参考
description: 处理最后的数据块并计算输出值。
type: docs
weight: 66
url: /zh/system.security.cryptography/tobase64transform/transformfinalblock/
---
## ToBase64Transform::TransformFinalBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) 方法

处理最后的数据块并计算输出值。

```cpp
System::ArrayPtr<uint8_t> System::Security::Cryptography::ToBase64Transform::TransformFinalBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用于读取数据。 |
| inputOffset | **int32_t** | 输入缓冲区偏移。 |
| inputCount | **int32_t** | 要处理的字节数。 |

### 返回值

针对整个输入序列计算的输出。

## 参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [ToBase64Transform](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)