---
title: Copy()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的文件复制到指定位置。如果目标文件已存在，则有一个参数指定是否应覆盖它。
type: docs
weight: 40
url: /zh/system.io/file/copy/
---
## File::Copy(const String\&, const String\&, bool) 方法

将指定的文件复制到指定位置。如果目标文件已经存在，则参数指定是否应覆盖它。

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | 要复制的文件的路径 |
| destFileName | const [String](../../../system/string/)\& | 要复制的文件的新位置路径 |
| overwrite | **bool** | 如果应覆盖已存在的目标文件则为 true；如果目标文件已存在且不应覆盖，则复制会失败，为 false |

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [File](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)