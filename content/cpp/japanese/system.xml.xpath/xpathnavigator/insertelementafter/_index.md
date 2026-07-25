---
title: InsertElementAfter()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前空間プレフィックス、ローカル名、名前空間URI、および指定された値を使用して、現在のノードの後に新しい兄弟要素を作成します。
type: docs
weight: 1028
url: /ja/system.xml.xpath/xpathnavigator/insertelementafter/
---
## XPathNavigator::InsertElementAfter(String, String, String, String) メソッド


現在のノードの後に、新しい兄弟要素を、指定された名前空間プレフィックス、ローカル名、名前空間URI、および指定された値を使用して作成します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementAfter(String prefix, String localName, String namespaceURI, String value)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 新しい子要素の名前空間プレフィックス（存在する場合）。 |
| localName | [String](../../../system/string/) | 新しい子要素のローカル名（存在する場合）。 |
| namespaceURI | [String](../../../system/string/) | 新しい子要素の名前空間URI（存在する場合）。[String::Empty](../../../system/string/empty/) と **nullptr** は同等です。 |
| value | [String](../../../system/string/) | 新しい子要素の値。[String::Empty](../../../system/string/empty/) または **nullptr** が渡された場合、空の要素が作成されます。 |

## 関連項目

* クラス [String](../../../system/string/)
* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)