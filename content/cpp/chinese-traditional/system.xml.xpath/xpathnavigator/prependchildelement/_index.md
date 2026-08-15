---
title: PrependChildElement()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的命名空間前綴、本地名稱與命名空間 URI，並以指定的值，在當前節點的子節點列表開頭建立一個新的子元素。
type: docs
weight: 989
url: /zh-hant/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) 方法

在當前節點的子節點列表開頭建立一個新的子元素，使用指定的命名空間前綴、本地名稱與命名空間 URI，以及指定的值。

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 新子元素的命名空間前綴（如果有）。 |
| localName | [String](../../../system/string/) | 新子元素的本地名稱（如果有）。 |
| namespaceURI | [String](../../../system/string/) | 新子元素的命名空間 URI（如果有）。[String::Empty](../../../system/string/empty/) 和 **nullptr** 等價。 |
| value | [String](../../../system/string/) | 新子元素的值。若傳入 [String::Empty](../../../system/string/empty/) 或 **nullptr**，則會建立空元素。 |

## 另請參見

* 類別 [String](../../../system/string/)
* 類別 [XPathNavigator](../)
* 名稱空間 [System::Xml::XPath](../../)
* 程式庫 [Aspose.Slides](../../../)