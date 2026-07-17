---
title: CryptoStream()
second_title: Aspose.Slides for C++ API 参考
description: 构造函数。
type: docs
weight: 1
url: /zh/system.security.cryptography/cryptostream/cryptostream/
---
## CryptoStream::CryptoStream(const SharedPtr\<System::IO::Stream\>\&, const SharedPtr\<ICryptoTransform\>\&, CryptoStreamMode) 构造函数

构造函数。

```cpp
System::Security::Cryptography::CryptoStream::CryptoStream(const SharedPtr<System::IO::Stream> &stream, const SharedPtr<ICryptoTransform> &transform, CryptoStreamMode mode)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 要包装的流。 |
| transform | const [SharedPtr](../../../system/sharedptr/)\<[ICryptoTransform](../../icryptotransform/)\>\& | 在发送/读取流时用于处理数据的转换函数。 |
| mode | [CryptoStreamMode](../../cryptostreammode/) | 流的方向。 |

## 另见

* 枚举 [CryptoStreamMode](../../cryptostreammode/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../../system.io/stream/)
* 类 [ICryptoTransform](../../icryptotransform/)
* 类 [CryptoStream](../)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)