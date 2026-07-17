---
title: get_BaseStream()
second_title: Aspose.Slides for C++ API 参考
description: 返回底层流对象。
type: docs
weight: 1
url: /zh/system.xml/xmltextwriter/get_basestream/
---
## XmlTextWriter::get_BaseStream() 方法

返回底层流对象。

```cpp
SharedPtr<IO::Stream> System::Xml::XmlTextWriter::get_BaseStream()
```

### 返回值

流对象，[XmlTextWriter](../) 正在写入的流，或者如果 [XmlTextWriter](../) 是使用不继承自 StreamWriter 类的 TextWriter 构造的，则为 **nullptr**。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Stream](../../../system.io/stream/)
* 类 [XmlTextWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)