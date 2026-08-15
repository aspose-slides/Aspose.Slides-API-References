---
title: SelectSingleNode()
second_title: Aspose.Slides for C++ API 參考文件
description: 選取第一個符合 XPath 表達式的 XmlNode。
type: docs
weight: 352
url: /zh-hant/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) method

選取第一個符合 [XPath](../../../system.xml.xpath/) 運算式的 [XmlNode](../)。

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) 運算式。 |

### 返回值

符合 [XPath](../../../system.xml.xpath/) 查詢的第一個 [XmlNode](../)，若未找到匹配的節點則回傳 **nullptr**。

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method

選取第一個符合 [XPath](../../../system.xml.xpath/) 運算式的 [XmlNode](../)。在 [XPath](../../../system.xml.xpath/) 運算式中發現的任何前綴，皆使用提供的 [XmlNamespaceManager](../../xmlnamespacemanager/) 進行解析。

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) 運算式。 |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | 用於在 [XPath](../../../system.xml.xpath/) 運算式中解析前綴命名空間的 [XmlNamespaceManager](../../xmlnamespacemanager/)。 |

### 返回值

符合 [XPath](../../../system.xml.xpath/) 查詢的第一個 [XmlNode](../)，若未找到匹配的節點則回傳 **nullptr**。

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../)
* 類別 [String](../../../system/string/)
* 類別 [XmlNamespaceManager](../../xmlnamespacemanager/)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)