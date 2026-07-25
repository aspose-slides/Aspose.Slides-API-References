---
title: AppendChildElement()
second_title: Aspose.Slides for C++ APIリファレンス
description: 現在のノードの子ノードリストの末尾に、新しい子要素ノードを、指定された名前空間プレフィックス、ローカル名、および名前空間URIとその値を使用して作成します。
type: docs
weight: 1002
url: /ja/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) メソッド


現在のノードの子ノードリストの末尾に、新しい子要素ノードを、指定された名前空間プレフィックス、ローカル名、名前空間 URI とその値を使用して作成します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```


### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 新しい子要素ノードの名前空間プレフィックス（該当する場合）。 |
| localName | [String](../../../system/string/) | 新しい子要素ノードのローカル名（該当する場合）。 |
| namespaceURI | [String](../../../system/string/) | 新しい子要素ノードの名前空間 URI（該当する場合）。[String::Empty](../../../system/string/empty/) と **nullptr** は同等です。 |
| value | [String](../../../system/string/) | 新しい子要素ノードの値。[String::Empty](../../../system/string/empty/) または **nullptr** が渡された場合、空の要素が作成されます。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)