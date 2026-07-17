---
title: StreamReader()
second_title: Aspose.Slides C++ API 参考
description: 构造一个 StreamReader 对象实例，该对象使用 UTF-8 编码并使用默认大小为 1024 字节的缓冲区，从指定的底层流读取字符。
type: docs
weight: 1
url: /zh/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) 构造函数

构造一个 [StreamReader](../) 对象实例，该对象使用 UTF-8 编码并使用默认大小为 1024 字节的缓冲区从指定的底层流读取字符。

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 要读取字符的底层流 |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) 构造函数

构造一个 [StreamReader](../) 对象实例，该对象使用 UTF-8 编码并使用默认大小为 1024 字节的缓冲区从指定的底层流读取字符。一个参数指定是否应启用字节顺序标记检测。

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 要读取字符的底层流 |
| detectEncodingFromByteOrderMarks | **bool** | True 表示在流的开头查找字节顺序标记，否则为 false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) 构造函数

构造一个 [StreamReader](../) 对象实例，该对象使用指定的编码并使用默认大小为 1024 字节的缓冲区从指定的底层流读取字符。

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 要读取字符的底层流 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的编码 |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) 构造函数

构造一个 [StreamReader](../) 对象实例，该对象使用指定的编码并使用默认大小为 1024 字节的缓冲区从指定的底层流读取字符。一个参数指定是否应启用字节顺序标记检测。

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 要读取字符的底层流 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的编码 |
| detectEncodingFromByteOrderMarks | **bool** | True 表示在流的开头查找字节顺序标记，否则为 false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) 构造函数

构造一个 [StreamReader](../) 对象实例，该对象使用指定的编码并使用指定大小的缓冲区从指定的底层流读取字符。一个参数指定是否应启用字节顺序标记检测。

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 要读取字符的底层流 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的编码 |
| detectEncodingFromByteOrderMarks | **bool** | True 表示在流的开头查找字节顺序标记，否则为 false |
| bufferSize | int | 缓冲区的最小大小（单位：字节） |

## StreamReader::StreamReader(const System::String\&) 构造函数

构造一个 [StreamReader](../) 对象实例，该对象使用 UTF-8 编码并使用默认大小为 4096 字节的缓冲区从指定文件读取字符。

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 要读取字符的文件路径 |

## StreamReader::StreamReader(const System::String\&, bool) 构造函数

构造一个 [StreamReader](../) 对象实例，该对象使用 UTF-8 编码并使用默认大小为 4096 字节的缓冲区从指定文件读取字符。一个参数指定是否应启用字节顺序标记检测。

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 要读取字符的文件路径 |
| detectEncodingFromByteOrderMarks | **bool** | True 表示在文件的开头查找字节顺序标记，否则为 false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) 构造函数

构造一个 [StreamReader](../) 对象实例，该对象使用指定的编码并使用默认大小为 4096 字节的缓冲区从指定文件读取字符。

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 要读取字符的文件路径 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的编码 |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) 构造函数

构造一个 [StreamReader](../) 对象实例，该对象使用指定的编码并使用默认大小为 4096 字节的缓冲区从指定的底层流读取字符。一个参数指定是否应启用字节顺序标记检测。

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 要读取字符的文件路径 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的编码 |
| detectEncodingFromByteOrderMarks | **bool** | True 表示在文件的开头查找字节顺序标记，否则为 false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) 构造函数

构造一个 [StreamReader](../) 对象实例，该对象使用指定的编码并使用指定大小的缓冲区从指定文件读取字符。一个参数指定是否应启用字节顺序标记检测。

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 要读取字符的文件路径 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的编码 |
| detectEncodingFromByteOrderMarks | **bool** | True 表示在文件的开头查找字节顺序标记，否则为 false |
| bufferSize | int | 缓冲区的最小大小（单位：字节） |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [EncodingPtr](../../../system/encodingptr/)
* 类 [Stream](../../stream/)
* 类 [StreamReader](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)