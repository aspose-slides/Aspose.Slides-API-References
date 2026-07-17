---
title: CheckPath()
second_title: Aspose.Slides for C++ API 参考
description: 通过检查路径是否包含无效字符来确定指定的路径是否有效。如果路径包含无效字符，将抛出异常。
type: docs
weight: 209
url: /zh/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) 方法

确定指定的路径是否有效，通过检查其是否包含无效字符。如果路径包含无效字符，将抛出异常。

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 用于检查的 path |
| msg | const [String](../../../system/string/)\& | 传递给异常对象构造函数的消息 |
| allow_empty | **bool** | 指定在空字符串或 null 字符串是否应被视为正确路径（true）或不正确（false）；如果此参数为 false 且 **path** 为空则抛出 ArgumentException；如果此参数为 false 且 **path** 为 null 则抛出 ArgumentNullException |

## 参见

* 类 [String](../../../system/string/)
* 类 [Path](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)