---
title: Replace()
second_title: Aspose.Slides C++ API 参考
description: 将一个文件的内容替换为另一个文件的内容，并为被替换的文件创建备份。
type: docs
weight: 339
url: /zh/system.io/file/replace/
---
## File::Replace(const String\&, const String\&, const String\&, bool) 方法

将一个文件的内容替换为另一个文件的内容，并为被替换的文件创建备份。

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | 用于替换的文件名 |
| destinationFileName | const [String](../../../system/string/)\& | 要被替换的文件名 |
| destinationBackupFileName | const [String](../../../system/string/)\& | 备份文件的名称 |
| ignoreMetadataErrors | **bool** | 指定是否应忽略从被替换文件到替换文件的合并错误（true）或不忽略（false） |

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [File](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)