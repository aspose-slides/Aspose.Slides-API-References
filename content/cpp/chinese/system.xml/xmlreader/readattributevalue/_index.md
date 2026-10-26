---
title: ReadAttributeValue()
second_title: Aspose.Slides for C++ API 参考
description: 在派生类中被重写时，将属性值解析为一个或多个 Text、EntityReference 或 EndEntity 节点。
type: docs
weight: 677
url: /zh/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() 方法

在派生类中被重写时，将属性值解析为一个或多个 **[Text](../../../system.text/)**、**EntityReference** 或 **EndEntity** 节点。

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```

### 返回值

**true** 如果有节点可返回。**false** 如果在初始调用时读取器未定位在属性节点或所有属性值已读取完毕。空属性，例如 **misc=\"\"**，返回 **true**，并带有一个值为 [String::Empty](../../../system/string/empty/) 的单一节点。

## 参见

* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)