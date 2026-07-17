---
title: get_IsEmptyElement()
second_title: Aspose.Slides C++ API 参考
description: 在派生类中被覆盖时，获取一个值，指示当前节点是否为空元素（例如，<MyElement/>）。
type: docs
weight: 131
url: /zh/system.xml/xmlreader/get_isemptyelement/
---
## XmlReader::get_IsEmptyElement() 方法


当在派生类中被覆盖时，获取一个值，指示当前节点是否为空元素（例如，**<MyElement/>**）。

```cpp
virtual bool System::Xml::XmlReader::get_IsEmptyElement()=0
```


### 返回值

**true** 如果当前节点是一个元素（[XmlReader::get_NodeType](../get_nodetype/) 等于 [XmlNodeType::Element](../../xmlnodetype/)）且以 **/>** 结尾；否则，**false**。

## 另请参见

* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)