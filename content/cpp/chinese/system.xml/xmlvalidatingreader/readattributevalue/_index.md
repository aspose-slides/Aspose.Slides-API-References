---
title: ReadAttributeValue()
second_title: Aspose.Slides for C++ API 参考
description: 将属性值解析为一个或多个 Text、EntityReference 或 EndEntity 节点。
type: docs
weight: 508
url: /zh/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() method


将属性值解析为一个或多个 **[Text](../../../system.text/)**、**EntityReference** 或 **EndEntity** 节点。

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```


### 返回值

**true** 如果有节点可以返回。**false** 如果在首次调用时读取器未定位在属性节点上，或所有属性值已被读取。空属性，例如 **misc=\"\"**，返回 **true** 并带有一个值为 [String::Empty](../../../system/string/empty/) 的单节点。

## 另请参见

* 类 [XmlValidatingReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)