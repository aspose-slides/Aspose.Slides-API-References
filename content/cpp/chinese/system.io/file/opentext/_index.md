---
title: OpenText()
second_title: Aspose.Slides for C++ API 参考
description: 以 UTF-8 编码打开指定的已存在文件进行文本读取，且不共享。
type: docs
weight: 261
url: /zh/system.io/file/opentext/
---
## File::OpenText(const String&, const EncodingPtr&) 方法


以 UTF-8 编码打开指定的已存在文件进行文本读取，且不共享。

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | 要打开的文件路径 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)& | 要使用的字符编码 |

### 返回值

一个指向与已打开文件关联的 [StreamWriter](../../streamwriter/) 对象的共享指针

## 另见

* 类型定义 [StreamReaderPtr](../../../system/streamreaderptr/)
* 类型定义 [EncodingPtr](../../../system/encodingptr/)
* 类 [String](../../../system/string/)
* 类 [File](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)