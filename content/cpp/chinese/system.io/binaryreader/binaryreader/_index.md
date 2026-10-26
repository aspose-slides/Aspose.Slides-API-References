---
title: BinaryReader()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个 BinaryReader 类的实例，该实例使用 UTF-8 编码从指定的流读取数据。
type: docs
weight: 1
url: /zh/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) 构造函数

构造一个 [BinaryReader](../) 类的实例，该实例使用 UTF-8 编码从指定的流读取数据。

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 输入流 |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) 构造函数

构造一个 [BinaryReader](../) 类的实例，该实例使用指定的编码从指定的流读取数据。

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 输入流 |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 要使用的编码 |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) 构造函数

构造一个 [BinaryReader](../) 类的实例，该实例使用指定的编码从指定的流读取数据。

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 输入流 |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 要使用的编码 |
| leaveOpen | **bool** | 指定在当前对象被释放后是否应保持 input 流打开 (true) 或关闭 (false) |

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../stream/)
* 类 [BinaryReader](../)
* 类 [Encoding](../../../system.text/encoding/)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)