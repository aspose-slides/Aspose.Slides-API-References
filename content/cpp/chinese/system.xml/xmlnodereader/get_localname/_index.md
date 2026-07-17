---
title: get_LocalName()
second_title: Aspose.Slides for C++ API 参考
description: 返回当前节点的本地名称。
type: docs
weight: 27
url: /zh/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName() 方法


返回当前节点的本地名称。

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```


### 返回值

当前节点的名称，已去除前缀。例如，**LocalName** 对元素 **<bk:book>** 为 **book**。对于没有名称的节点类型（如 **[Text](../../../system.text/)**、**Comment** 等），此方法返回 [String::Empty](../../../system/string/empty/)。

## 另见

* 类 [String](../../../system/string/)
* 类 [XmlNodeReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)