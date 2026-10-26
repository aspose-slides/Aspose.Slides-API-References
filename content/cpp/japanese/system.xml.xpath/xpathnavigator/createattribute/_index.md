---
title: CreateAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された値を使用して、現在の要素ノード上に名前空間プレフィックス、ローカル名、名前空間URIを指定した属性ノードを作成します。
type: docs
weight: 1041
url: /ja/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) メソッド

現在の要素ノード上に、指定された名前空間プレフィックス、ローカル名、および名前空間URIと、指定された値を使用して属性ノードを作成します。

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 新しい属性ノードの名前空間プレフィックス (該当する場合)。 |
| localName | [String](../../../system/string/) | 新しい属性ノードのローカル名で、[String::Empty](../../../system/string/empty/) または **nullptr** にすることはできません。 |
| namespaceURI | [String](../../../system/string/) | 新しい属性ノードの名前空間URI (該当する場合)。 |
| value | [String](../../../system/string/) | 新しい属性ノードの値。[String::Empty](../../../system/string/empty/) または **nullptr** が渡された場合、空の属性ノードが作成されます。 |

## 関連項目

* クラス [String](../../../system/string/)
* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)