---
title: Replace()
second_title: Aspose.Slides for C++ API 参考
description: 将指定目标文件的内容替换为当前 FileInfo 对象所表示的文件，并为被替换的文件创建备份。
type: docs
weight: 131
url: /zh/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) 方法

将指定目标文件的内容替换为当前 [FileInfo](../) 对象所表示的文件，并为被替换的文件创建备份。

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | 要替换的文件名 |
| destinationBackupFileName | const [String](../../../system/string/)\& | 备份文件的名称 |

### 返回值

一个表示由 **destinationFileName** 指向的文件的 FileInfor 对象

## FileInfo::Replace(const String\&, const String\&, bool) 方法

将指定目标文件的内容替换为当前 [FileInfo](../) 对象所表示的文件，并为被替换的文件创建备份。

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | 要替换的文件名 |
| destinationBackupFileName | const [String](../../../system/string/)\& | 备份文件的名称 |
| ignoreMetadataErrors | **bool** | 指定是否应忽略从被替换文件合并到替换文件的错误（true）或不忽略（false） |

### 返回值

一个表示由 **destinationFileName** 指向的文件的 FileInfor 对象

## 另见

* 类型定义 [FileInfoPtr](../../../system/fileinfoptr/)
* 类 [String](../../../system/string/)
* 类 [FileInfo](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)