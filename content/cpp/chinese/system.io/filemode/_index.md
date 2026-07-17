---
title: FileMode
second_title: Aspose.Slides for C++ API 参考
description: 指定应如何打开文件。
type: docs
weight: 508
url: /zh/system.io/filemode/
---
## FileMode 枚举

指定应如何打开文件。

```cpp
enum class FileMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| CreateNew | 1 | 创建一个新文件。如果文件已经存在，则会抛出异常。 |
| Create | 2 | 创建一个新文件。如果文件已经存在，则会被覆盖。 |
| Open | 3 | 打开一个已存在的文件。如果文件不存在，则会抛出异常。 |
| OpenOrCreate | 4 | 打开一个已存在的文件，或者如果不存在则创建一个新文件。 |
| Truncate | 5 | 打开一个已存在的文件并将其截断，使其为空。如果文件不存在，则会抛出异常。 |
| Append | 6 | 打开一个已存在的文件并定位到文件末尾，或者如果不存在则创建一个新文件。 |

## 另请参见

* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)