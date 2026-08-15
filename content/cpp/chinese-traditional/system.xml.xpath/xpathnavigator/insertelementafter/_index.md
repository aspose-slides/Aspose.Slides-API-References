---
title: InsertElementAfter()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用指定的命名空間前置詞、本地名稱與命名空間 URI，在目前節點之後建立新的同層元素，並設定指定的值。
type: docs
weight: 1028
url: /zh-hant/system.xml.xpath/xpathnavigator/insertelementafter/
---
## XPathNavigator::InsertElementAfter(String, String, String, String) 方法


建立一個新的同層元素，於目前節點之後，使用指定的命名空間前置詞、本地名稱與命名空間 URI，並設定指定的值。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementAfter(String prefix, String localName, String namespaceURI, String value)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 新子元素的命名空間前置詞（如果有的話）。 |
| localName | [String](../../../system/string/) | 新子元素的本地名稱（如果有的話）。 |
| namespaceURI | [String](../../../system/string/) | 新子元素的命名空間 URI（如果有的話）。[String::Empty](../../../system/string/empty/) 與 **nullptr** 等價。 |
| value | [String](../../../system/string/) | 新子元素的值。若傳入 [String::Empty](../../../system/string/empty/) 或 **nullptr**，將建立空元素。 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)