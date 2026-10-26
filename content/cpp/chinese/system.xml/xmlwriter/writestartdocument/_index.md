---
title: WriteStartDocument()
second_title: Aspose.Slides for C++ API 参考
description: 当在派生类中重写时，写入版本为 \"1.0\" 的 XML 声明。
type: docs
weight: 53
url: /zh/system.xml/xmlwriter/writestartdocument/
---
## XmlWriter::WriteStartDocument() 方法

当在派生类中重写时，写入版本为 \"1.0\" 的 XML 声明。

```cpp
virtual void System::Xml::XmlWriter::WriteStartDocument()=0
```

## XmlWriter::WriteStartDocument(bool) 方法

当在派生类中重写时，写入版本为 \"1.0\" 且包含 standalone 属性的 XML 声明。

```cpp
virtual void System::Xml::XmlWriter::WriteStartDocument(bool standalone)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| standalone | **bool** | 如果 **true**，则写入 \"standalone=yes\"；如果 **false**，则写入 \"standalone=no\"。 |

## 另请参见

* 类 [XmlWriter](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)