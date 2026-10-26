---
title: FileShare
second_title: Aspose.Slides for C++ API 参考
description: 指定其他 FileStream 对象对正在打开的文件可以拥有的访问类型。
type: docs
weight: 534
url: /zh/system.io/fileshare/
---
## FileShare 枚举

指定其他 [FileStream](../filestream/) 对象对正在打开的文件可以拥有何种访问权限。

```cpp
enum class FileShare
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 无访问权限。 |
| Read | 1 | 只读访问。 |
| Write | 2 | 只写访问。 |
| ReadWrite | 3 | 读写访问。 |
| Delete | 4 | 可以删除该文件。 |
| Inheritable | 16 | 使文件句柄可被子进程继承。 |

## 另请参阅

* 命名空间 [System::IO](../)
* 库 [Aspose.Slides](../../)