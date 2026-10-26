---
title: BinaryWriter()
second_title: Aspose.Slides for C++ API 参考
description: 构造 BinaryWriter 类的实例，该实例使用指定的编码将数据写入指定的流。
type: docs
weight: 1
url: /zh/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) 构造函数

构造一个 [BinaryWriter](../) 类的实例，该实例使用指定的编码将数据写入指定的流。

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 输出流 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的编码 |
| leaveopen | **bool** | 指定在当前对象被释放后，流 **stream** 是否应保持打开（true）或关闭（false） |

## 参见

* 类型定义 [StreamPtr](../../../system/streamptr/)
* 类型定义 [EncodingPtr](../../../system/encodingptr/)
* 类 [BinaryWriter](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)