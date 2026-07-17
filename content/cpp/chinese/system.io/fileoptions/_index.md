---
title: FileOptions
second_title: Aspose.Slides for C++ API 参考
description: 表示用于创建 FileStream 对象的高级选项。
type: docs
weight: 521
url: /zh/system.io/fileoptions/
---
## FileOptions 枚举

表示用于创建 [FileStream](../filestream/) 对象的高级选项。

```cpp
enum class FileOptions
```

### 值

| 名称 | 数值 | 描述 |
| --- | --- | --- |
| None | 0 | 没有其他选项。 |
| Encrypted | 16384 | 文件已加密。未实现。 |
| DeleteOnClose | 67108864 | 当文件不再使用时，应该自动删除。 |
| SequentialScan | 134217728 | 文件应顺序访问。 |
| RandomAccess | 268435456 | 文件被随机访问。 |
| Asynchronous | 1073741824 | 文件可用于异步 I/O 操作。 |
| WriteThrough | n/a | 所有写入应直接写入磁盘，绕过任何中间缓存。 |

## 另请参见

* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)