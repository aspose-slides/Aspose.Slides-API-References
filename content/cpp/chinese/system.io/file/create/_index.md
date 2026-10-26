---
title: Create()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的缓冲区大小和选项创建新文件（或覆盖已存在的文件），并以读取和写入模式打开它。
type: docs
weight: 53
url: /zh/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) 方法

创建一个新文件（或覆盖已有文件），并使用指定的缓冲区大小和选项以读取和写入访问方式打开它。

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要创建或覆盖的文件的路径 |
| bufferSize | **int32_t** | 从文件读取和写入时缓冲的字节数 |
| options | [FileOptions](../../fileoptions/) | 指定如何创建或覆盖文件 |

### 返回值

与指定文件关联的[FileStream](../../filestream/)对象的共享指针

## 另见

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)