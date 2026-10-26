---
title: XPathNodeType
second_title: Aspose.Slides for C++ API 參考文件
description: 定義可由 XPathNavigator 類別返回的 XPath 節點類型。
type: docs
weight: 157
url: /zh-hant/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum

定義 [XPath](../) 節點類型，這些類型可以由 [XPathNavigator](../xpathnavigator/) 類別返回。

```cpp
enum class XPathNodeType
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Root | 0 | XML 文件或節點樹的根節點。 |
| Element | 1 | 元素，例如 **<element>**。 |
| Attribute | 2 | 屬性，例如 **id='123'**。 |
| Namespace | 3 | 命名空間，例如 **xmlns=\"namespace\"**。 |
| Text | 4 | 節點的文字內容。相當於 Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) 與 CDATA 節點類型。至少包含一個字元。 |
| SignificantWhitespace | 5 | 包含空白字元且 **xml:space** 設為 **preserve** 的節點。 |
| Whitespace | 6 | 僅包含空白字元且沒有顯著空白的節點。空白字元包括 **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**。 |
| ProcessingInstruction | 7 | 處理指令，例如 **<?pi test?>**。此不含 XML 宣告，因為它們對 [XPathNavigator](../xpathnavigator/) 類別不可見。 |
| Comment | 8 | 註解，例如 ****。 |
| All | 9 | 任一 XPathNodeType 節點類型。 |

## 另請參閱

* 命名空間 [System::Xml::XPath](../)
* 函式庫 [Aspose.Slides](../../)