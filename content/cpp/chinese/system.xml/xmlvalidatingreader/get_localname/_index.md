---
title: get_LocalName()
second_title: Aspose.Slides C++ API 参考文档
description: 返回当前节点的本地名称。
type: docs
weight: 27
url: /zh/system.xml/xmlvalidatingreader/get_localname/
---
## XmlValidatingReader::get_LocalName() 方法


返回当前节点的本地名称。

```cpp
String System::Xml::XmlValidatingReader::get_LocalName() override
```


### 返回值

返回已去除前缀的当前节点名称。例如，**LocalName** 对于元素 **<bk:book>** 为 **book**。对于没有名称的节点类型（如 **[Text](../../../system.text/)**、**Comment** 等），此方法返回 [String::Empty](../../../system/string/empty/)。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlValidatingReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)