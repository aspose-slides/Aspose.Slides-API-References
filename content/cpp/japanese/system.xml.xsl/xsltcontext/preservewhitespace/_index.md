---
title: PreserveWhitespace()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、指定されたコンテキストに対して空白ノードを保持するか除去するかを評価します。
type: docs
weight: 40
url: /ja/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) メソッド

派生クラスでオーバーライドされた場合、指定されたコンテキストに対して空白ノードを保持するか除去するかを評価します。

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | 現在のコンテキストで保持または除去される空白ノードです。 |

### 戻り値

**true** は空白が保持されることを示し、**false** は空白が除去されることを示します。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* クラス [XsltContext](../)
* 名前空間 [System::Xml::Xsl](../../)
* ライブラリ [Aspose.Slides](../../../)