---
title: AppendChildElement()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的名稱空間前置詞、本機名稱與名稱空間 URI，並以指定的值，在目前節點的子節點清單末端建立新子元素節點。
type: docs
weight: 1002
url: /zh-hant/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) 方法

建立一個新的子元素節點，將其加入目前節點的子節點清單末端，使用指定的名稱空間前置詞、本機名稱以及名稱空間 URI，並以指定的值設定。

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 新子元素節點的名稱空間前置詞（如果有）。 |
| localName | [String](../../../system/string/) | 新子元素節點的本機名稱（如果有）。 |
| namespaceURI | [String](../../../system/string/) | 新子元素節點的名稱空間 URI（如果有）。[String::Empty](../../../system/string/empty/) 與 **nullptr** 等價。 |
| value | [String](../../../system/string/) | 新子元素節點的值。如果傳入 [String::Empty](../../../system/string/empty/) 或 **nullptr**，則會建立一個空元素。 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)