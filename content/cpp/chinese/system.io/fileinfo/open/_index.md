---
title: Open()
second_title: Aspose.Slides for C++ API 参考
description: 以指定模式打开当前对象表示的文件，用于读取和写入，并且不共享。
type: docs
weight: 183
url: /zh/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) 方法

以指定模式打开当前对象表示的文件，用于读取和写入，并且不共享。

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | 指定打开文件的模式 |

### 返回值

与当前对象表示的文件关联的 [FileStream](../../filestream/) 对象

## FileInfo::Open(FileMode, FileAccess) 方法

以指定模式打开当前对象表示的文件，使用指定的访问类型，并且不共享。

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | 指定打开文件的模式 |
| access | [FileAccess](../../fileaccess/) | 请求的访问类型 |

### 返回值

与当前对象表示的文件关联的 [FileStream](../../filestream/) 对象

## FileInfo::Open(FileMode, FileAccess, FileShare) 方法

以指定模式打开当前对象表示的文件，使用指定的访问类型和共享选项。

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | 指定打开文件的模式 |
| access | [FileAccess](../../fileaccess/) | 请求的访问类型 |
| share | [FileShare](../../fileshare/) | 其他 [FileStream](../../filestream/) 对象对已打开文件拥有的访问类型 |

### 返回值

与当前对象表示的文件关联的 [FileStream](../../filestream/) 对象

## 另请参见

* 枚举 [FileMode](../../filemode/)
* 枚举 [FileAccess](../../fileaccess/)
* 枚举 [FileShare](../../fileshare/)
* 类型定义 [FileStreamPtr](../../../system/filestreamptr/)
* 类 [FileInfo](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)