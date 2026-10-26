---
title: InsertElementBefore()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前空間プレフィックス、ローカル名、および名前空間 URI を使用し、指定された値で、現在のノードの前に新しい兄弟要素を作成します。
type: docs
weight: 1015
url: /ja/system.xml.xpath/xpathnavigator/insertelementbefore/
---
## XPathNavigator::InsertElementBefore(String, String, String, String) メソッド


指定された名前空間プレフィックス、ローカル名、および名前空間 URI を使用して、現在のノードの前に新しい兄弟要素を作成し、指定された値を設定します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementBefore(String prefix, String localName, String namespaceURI, String value)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 新しい子要素の名前空間プレフィックス（該当する場合）。 |
| localName | [String](../../../system/string/) | 新しい子要素のローカル名（該当する場合）。 |
| namespaceURI | [String](../../../system/string/) | 新しい子要素の名前空間 URI（該当する場合）。[String::Empty](../../../system/string/empty/) と **nullptr** は等価です。 |
| value | [String](../../../system/string/) | 新しい子要素の値。[String::Empty](../../../system/string/empty/) または **nullptr** が渡された場合、空の要素が作成されます。 |

## 関連項目

* クラス [String](../../../system/string/)
* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)