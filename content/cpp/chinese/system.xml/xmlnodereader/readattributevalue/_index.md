---
title: ReadAttributeValue()
second_title: Aspose.Slides for C++ API 参考
description: 将属性值解析为一个或多个 Text、EntityReference 或 EndEntity 节点。
type: docs
weight: 430
url: /zh/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() method


将属性值解析为一个或多个 **[Text](../../../system.text/)**, **EntityReference**, 或 **EndEntity** 节点。

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```


### 返回值

**true** 如果有节点返回。**false** 如果在首次调用时读取器未定位在属性节点上，或所有属性值已被读取。空属性，例如 **misc=\"\"**, 返回 **true** 并且只有一个节点，其值为 [String::Empty](../../../system/string/empty/)。

## 另请参见

* 类 [XmlNodeReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)