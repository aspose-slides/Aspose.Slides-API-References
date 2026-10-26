---
title: SelectSingleNode()
second_title: Aspose.Slides for C++ API リファレンス
description: XPath 式に一致する最初の XmlNode を選択します。
type: docs
weight: 352
url: /ja/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) メソッド

最初の[XmlNode](../)で、[XPath](../../../system.xml.xpath/)式に一致するものを選択します。

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/)式 |

### 戻り値

一致する[XPath](../../../system.xml.xpath/)クエリに一致する最初の[XmlNode](../)、または一致するノードが見つからない場合は**nullptr**です。

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) メソッド

[XmlNode](../)のうち最初のものを選択し、[XPath](../../../system.xml.xpath/)式に一致させます。[XPath](../../../system.xml.xpath/)式で見つかったプレフィックスは、提供された[XmlNamespaceManager](../../xmlnamespacemanager/)を使用して解決されます。

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/)式 |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/)を使用して、[XPath](../../../system.xml.xpath/)式のプレフィックスの名前空間を解決します。 |

### 戻り値

一致する[XPath](../../../system.xml.xpath/)クエリに一致する最初の[XmlNode](../)、または一致するノードが見つからない場合は**nullptr**です。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../)
* クラス [String](../../../system/string/)
* クラス [XmlNamespaceManager](../../xmlnamespacemanager/)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)