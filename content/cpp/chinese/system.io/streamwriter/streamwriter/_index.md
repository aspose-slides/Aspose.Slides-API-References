---
title: StreamWriter()
second_title: Aspose.Slides C++ API 参考
description: 构造一个 StreamWriter 对象，该对象使用 UTF-8 编码并使用默认大小为 1024 字节的缓冲区，将字符写入指定的底层流。
type: docs
weight: 1
url: /zh/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) 构造函数

构造一个 [StreamWriter](../) 对象，该对象使用 UTF-8 编码并使用默认大小为 1024 字节的缓冲区，将字符写入指定的底层流。

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 用于写入字符的底层流 |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) 构造函数

构造一个 [StreamWriter](../) 对象，该对象使用指定的编码并使用默认大小为 1024 字节的缓冲区，将字符写入指定的底层流。

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 用于写入字符的底层流 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的编码 |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) 构造函数

构造一个 [StreamWriter](../) 对象，该对象使用指定的编码和指定大小的缓冲区，将字符写入指定的底层流。当 [StreamWriter](../) 对象被释放时，一个参数指定是否应关闭底层流。

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 用于写入字符的底层流 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的编码 |
| buffer_size | int | 缓冲区的最小大小（字节） |
| leave_open | **bool** | 指定在当前 [StreamWriter](../) 对象被释放后，是否应保持底层流打开 |

## StreamWriter::StreamWriter(const String\&) 构造函数

构造一个 [StreamWriter](../) 对象，该对象使用 UTF-8 编码并使用默认大小为 1024 字节的缓冲区，将字符写入指定的文件。

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 用于写入字符的文件路径 |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) 构造函数

构造一个 [StreamWriter](../) 对象，该对象使用指定的编码并使用默认大小为 1024 字节的缓冲区，将字符写入指定的文件。一个参数指定是将数据追加到文件还是覆盖文件。

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 用于写入字符的文件路径 |
| append | **bool** | 指定是将数据追加到指定文件 (true) 还是覆盖文件 (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的编码 |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) 构造函数

构造一个 [StreamWriter](../) 对象，该对象使用指定的编码和指定的缓冲区大小，将字符写入指定的文件。一个参数指定是将数据追加到文件还是覆盖文件。

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 用于写入字符的文件路径 |
| append | **bool** | 指定是将数据追加到指定文件 (true) 还是覆盖文件 (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的编码 |
| buffer_size | int | 要使用的缓冲区大小 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [EncodingPtr](../../../system/encodingptr/)
* 类 [Stream](../../stream/)
* 类 [StreamWriter](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)