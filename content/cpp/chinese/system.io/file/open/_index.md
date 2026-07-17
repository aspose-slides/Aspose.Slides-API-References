---
title: Open()
second_title: Aspose.Slides C++ API 参考
description: 在指定模式下打开指定文件进行读取和写入，且不共享。
type: docs
weight: 235
url: /zh/system.io/file/open/
---
## File::Open(const String\&, FileMode) 方法

在指定模式下打开指定文件进行读取和写入，且不共享。

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要打开的文件的路径 |
| mode | [FileMode](../../filemode/) | 指定打开文件的模式 |

### 返回值

一个与已打开文件关联的 [FileStream](../../filestream/) 对象

## File::Open(const String\&, FileMode, FileAccess, FileShare) 方法

在指定模式下打开指定文件，并使用指定的访问类型和共享选项。

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要打开的文件的路径 |
| mode | [FileMode](../../filemode/) | 指定打开文件的模式 |
| access | [FileAccess](../../fileaccess/) | 请求的访问类型 |
| share | [FileShare](../../fileshare/) | 其他 [FileStream](../../filestream/) 对象对已打开文件拥有的访问类型 |

### 返回值

一个与已打开文件关联的 [FileStream](../../filestream/) 对象

## 另见

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* 类 [String](../../../system/string/)
* 类 [File](../)
* 命名空间 [System::IO](../../)
* Library [Aspose.Slides](../../../)