---
title: AppendText()
second_title: Aspose.Slides C++ API 参考
description: 创建一个使用 UTF-8 编码将文本追加到指定文件的 StreamWriter 对象。如果指定的文件不存在，将会创建它。
type: docs
weight: 27
url: /zh/system.io/file/appendtext/
---
## File::AppendText(const String\&) 方法


Creates a [StreamWriter](../../streamwriter/) object that appends text to the specified file using UTF-8 encoding. If the specified file does not exist, it is created.

```cpp
static StreamWriterPtr System::IO::File::AppendText(const String &path)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to open or create |

### 返回值

一个指向创建的 [StreamWriter](../../streamwriter/) 对象的共享指针，该对象与指定的文件关联

## 另见

* 类型定义 [StreamWriterPtr](../../../system/streamwriterptr/)
* 类 [String](../../../system/string/)
* 类 [File](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)