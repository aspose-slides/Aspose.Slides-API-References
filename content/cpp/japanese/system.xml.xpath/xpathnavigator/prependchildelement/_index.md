---
title: PrependChildElement()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードの子ノードリストの先頭に、指定された名前空間プレフィックス、ローカル名、および名前空間 URI と値を使用して、新しい子要素を作成します。
type: docs
weight: 989
url: /ja/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) メソッド

現在のノードの子ノードリストの先頭に、指定された名前空間プレフィックス、ローカル名、名前空間 URI と値を使用して、新しい子要素を作成します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 新しい子要素の名前空間プレフィックス（該当する場合）。 |
| localName | [String](../../../system/string/) | 新しい子要素のローカル名（該当する場合）。 |
| namespaceURI | [String](../../../system/string/) | 新しい子要素の名前空間 URI（該当する場合）。[String::Empty](../../../system/string/empty/) と **nullptr** は同等です。 |
| value | [String](../../../system/string/) | 新しい子要素の値。[String::Empty](../../../system/string/empty/) または **nullptr** が渡された場合、空の要素が作成されます。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)