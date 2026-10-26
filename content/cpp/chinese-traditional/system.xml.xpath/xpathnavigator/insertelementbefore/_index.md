---
title: InsertElementBefore()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用指定的命名空間前綴、本地名稱和命名空間 URI，在目前節點之前建立一個新的同級元素，並設定其值。
type: docs
weight: 1015
url: /zh-hant/system.xml.xpath/xpathnavigator/insertelementbefore/
---
## XPathNavigator::InsertElementBefore(String, String, String, String) 方法

使用指定的命名空間前綴、本地名稱和命名空間 URI，在目前節點之前建立一個新的同級元素，並設定其值。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementBefore(String prefix, String localName, String namespaceURI, String value)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 新子元素的命名空間前綴（如果有）。 |
| localName | [String](../../../system/string/) | 新子元素的本地名稱（如果有）。 |
| namespaceURI | [String](../../../system/string/) | 新子元素的命名空間 URI（如果有）。 [String::Empty](../../../system/string/empty/) 和 **nullptr** 等價。 |
| value | [String](../../../system/string/) | 新子元素的值。若傳入 [String::Empty](../../../system/string/empty/) 或 **nullptr**，則會建立空元素。 |

## 另見

* 類別 [String](../../../system/string/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)