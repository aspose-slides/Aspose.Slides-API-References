---
title: get_BaseURI()
second_title: Aspose.Slides C++ API 參考文件
description: 返回節點的基本統一資源標識符 (URI)。
type: docs
weight: 183
url: /zh-hant/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI() 方法

Returns the base Uniform Resource Identifier (URI) of the node.

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```

### 返回值

The location from which the node was loaded or [String::Empty](../../../system/string/empty/) if the node has no base URI. [Attribute](../../../system/attribute/) nodes have the same base URI as their owner element. If an attribute node does not have an owner element, get_BaseURI returns [String::Empty](../../../system/string/empty/).

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlAttribute](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)