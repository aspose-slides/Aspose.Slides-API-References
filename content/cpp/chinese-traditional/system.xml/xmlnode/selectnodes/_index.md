---
title: SelectNodes()
second_title: Aspose.Slides for C++ API 參考文件
description: 選取與 XPath 表達式相符的節點清單。
type: docs
weight: 365
url: /zh-hant/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) method

選擇與 [XPath](../../../system.xml.xpath/) 表達式相符的節點清單。

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | 此 [XPath](../../../system.xml.xpath/) 表達式。 |

### 回傳值

一個包含與 [XPath](../../../system.xml.xpath/) 查詢相符之節點集合的 [XmlNodeList](../../xmlnodelist/)。

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method

選擇與 [XPath](../../../system.xml.xpath/) 表達式相符的節點清單。任何在 [XPath](../../../system.xml.xpath/) 表達式中找到的前綴皆使用提供的 [XmlNamespaceManager](../../xmlnamespacemanager/) 進行解析。

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | 此 [XPath](../../../system.xml.xpath/) 表達式。 |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | 用於解析 [XPath](../../../system.xml.xpath/) 表達式中前綴之名稱空間的 [XmlNamespaceManager](../../xmlnamespacemanager/)。 |

### 回傳值

一個包含與 [XPath](../../../system.xml.xpath/) 查詢相符之節點集合的 [XmlNodeList](../../xmlnodelist/)。

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNodeList](../../xmlnodelist/)
* 類別 [String](../../../system/string/)
* 類別 [XmlNode](../)
* 類別 [XmlNamespaceManager](../../xmlnamespacemanager/)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)