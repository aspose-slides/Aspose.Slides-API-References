---
title: CopyTo()
second_title: Aspose.Slides for C++ API 参考
description: 将当前对象表示的文件复制到指定位置。如果目标文件已存在，复制将失败。
type: docs
weight: 105
url: /zh/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) 方法

将当前对象代表的文件复制到指定位置。如果目标文件已存在，复制将失败。

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | 目标文件名 |

### 返回值

一个 [FileInfo](../) 对象，表示复制

## FileInfo::CopyTo(const String\&, bool) 方法

将当前对象代表的文件复制到指定位置。一个参数指定是否应覆盖已存在的目标文件。

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | 目标文件名 |
| overwrite | **bool** | 如果应覆盖已存在的目标文件则为true；如果目标文件已存在且复制应失败则为false |

### 返回值

一个 [FileInfo](../) 对象，表示复制

## 另见

* 类型定义 [FileInfoPtr](../../../system/fileinfoptr/)
* 类 [String](../../../system/string/)
* 类 [FileInfo](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)