---
title: BufferedStream()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个 BufferedStream 对象，该对象包装指定的流并使用 4096 字节长的缓冲区。
type: docs
weight: 1
url: /zh/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) 构造函数

构造一个[BufferedStream](../)对象，该对象包装指定的流并使用4096字节长的缓冲区。

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 底层的[Stream](../../stream/)对象 |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) 构造函数

构造一个[BufferedStream](../)对象，该对象包装指定的流并使用指定大小的缓冲区。

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 底层的[Stream](../../stream/)对象 |
| bufferSize | int | 缓冲区的大小（字节） |

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../stream/)
* 类 [BufferedStream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)