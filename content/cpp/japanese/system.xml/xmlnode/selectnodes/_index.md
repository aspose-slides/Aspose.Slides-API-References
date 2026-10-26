---
title: SelectNodes()
second_title: Aspose.Slides for C++ API リファレンス
description: XPath式に一致するノードのリストを選択します。
type: docs
weight: 365
url: /ja/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) method

[XPath](../../../system.xml.xpath/) 式に一致するノードのリストを選択します。

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) 式。 |

### 戻り値

[XmlNodeList](../../xmlnodelist/) は、[XPath](../../../system.xml.xpath/) クエリに一致するノードのコレクションを含みます。

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method

[XPath](../../../system.xml.xpath/) 式に一致するノードのリストを選択します。[XPath](../../../system.xml.xpath/) 式で見つかったプレフィックスは、提供された [XmlNamespaceManager](../../xmlnamespacemanager/) を使用して解決されます。

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) 式。 |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XPath](../../../system.xml.xpath/) 式のプレフィックスの名前空間を解決するために使用する [XmlNamespaceManager](../../xmlnamespacemanager/)。 |

### 戻り値

[XmlNodeList](../../xmlnodelist/) は、[XPath](../../../system.xml.xpath/) クエリに一致するノードのコレクションを含みます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNodeList](../../xmlnodelist/)
* クラス [String](../../../system/string/)
* クラス [XmlNode](../)
* クラス [XmlNamespaceManager](../../xmlnamespacemanager/)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)