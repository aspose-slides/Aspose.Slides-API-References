---
title: Delete()
second_title: Aspose.Slides for C++ API 参考
description: 删除指定的文件或目录。不会抛出异常。
type: docs
weight: 14
url: /zh/system.io/directory/delete/
---
## Directory::Delete(const String&, bool) 方法

删除指定的文件或目录。不会抛出异常。

```cpp
static void System::IO::Directory::Delete(const String &path, bool recursive=false)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要删除的目录或文件的路径 |
| recursive | **bool** | 如果 **path** 指定了一个非空目录，则 **recursive** 指定是否应递归删除目录的所有内容；如果 **path** 指定的目录非空且 **recursive** 为 'false'，则操作失败 |

## 另见

* 类 [String](../../../system/string/)
* 类 [Directory](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)