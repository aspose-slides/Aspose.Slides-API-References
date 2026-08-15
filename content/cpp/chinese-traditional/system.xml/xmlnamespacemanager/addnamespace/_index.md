---
title: AddNamespace()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的名稱空間新增至集合中。
type: docs
weight: 66
url: /zh-hant/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) 方法

將指定的名稱空間新增至集合中。

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 要與所加入的名稱空間關聯的前置詞。使用 [String::Empty](../../../system/string/empty/) 來加入預設名稱空間。若 [XmlNamespaceManager](../) 將用於在 XML 路徑語言 ([XPath](../../../system.xml.xpath/)) 表達式中解析名稱空間，必須指定前置詞。若 [XPath](../../../system.xml.xpath/) 表達式未包含前置詞，則假設名稱空間的統一資源識別符 (URI) 為空名稱空間。欲取得關於 [XPath](../../../system.xml.xpath/) 表達式與 [XmlNamespaceManager](../) 的更多資訊，請參閱 XmlNode::SelectNodes(String) 與 XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) 方法。 |
| uri | [String](../../../system/string/) | 要加入的名稱空間。 |

## 參見

* 類別 [String](../../../system/string/)
* 類別 [XmlNamespaceManager](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)