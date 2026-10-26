---
title: CreateAttribute()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用指定的命名空間前置詞、本機名稱與命名空間 URI，並以指定的值在目前的元素節點上建立屬性節點。
type: docs
weight: 1041
url: /zh-hant/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) 方法

在目前的元素節點上建立屬性節點，使用指定的命名空間前置詞、本地名稱和命名空間 URI，並以指定的值。

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 新屬性節點的命名空間前置詞（如果有的話）。 |
| localName | [String](../../../system/string/) | 新屬性節點的本機名稱，不能 [String::Empty](../../../system/string/empty/) 或 **nullptr**。 |
| namespaceURI | [String](../../../system/string/) | 新屬性節點的命名空間 URI（如果有的話）。 |
| value | [String](../../../system/string/) | 新屬性節點的值。如果傳入 [String::Empty](../../../system/string/empty/) 或 **nullptr**，將建立一個空的屬性節點。 |

## 參見

* 類別 [String](../../../system/string/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)