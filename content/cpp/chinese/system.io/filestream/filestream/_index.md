---
title: FileStream()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新的 FileStream 类实例，并使用指定的参数进行初始化。
type: docs
weight: 1
url: /zh/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) 构造函数

构造一个新的 [FileStream](../) 类实例，并使用指定的参数进行初始化。

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要打开的文件路径。 |
| mode | [FileMode](../../filemode/) | 指定打开文件的模式。 |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) 构造函数

构造一个新的 [FileStream](../) 类实例，并使用指定的参数进行初始化。

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要打开的文件路径。 |
| mode | [FileMode](../../filemode/) | 指定打开文件的模式。 |
| access | [FileAccess](../../fileaccess/) | 请求的访问类型。 |
| share | [FileShare](../../fileshare/) | 其他 [FileStream](../) 对象对已打开文件拥有的访问类型。 |
| buffer_size | **int32_t** | 读写操作期间缓冲的字节数。 |
| options | [FileOptions](../../fileoptions/) | 附加选项。 |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) 构造函数

构造一个新的 [FileStream](../) 类实例，并使用指定的参数进行初始化。

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要打开的文件路径。 |
| mode | [FileMode](../../filemode/) | 指定打开文件的模式。 |
| access | [FileAccess](../../fileaccess/) | 请求的访问类型。 |
| share | [FileShare](../../fileshare/) | 其他 [FileStream](../) 对象对已打开文件拥有的访问类型。 |
| buffer_size | **int32_t** | 读写操作期间缓冲的字节数。 |
| useAsync | **bool** | 指定是使用异步 I/O 还是同步 I/O。 |

## 备注

底层操作系统可能不支持异步 I/O。

## FileStream::FileStream(const FileStream\&) 构造函数

```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## 参见

* 枚举 [FileMode](../../filemode/)
* 枚举 [FileAccess](../../fileaccess/)
* 枚举 [FileShare](../../fileshare/)
* 枚举 [FileOptions](../../fileoptions/)
* 类 [String](../../../system/string/)
* 类 [FileStream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)