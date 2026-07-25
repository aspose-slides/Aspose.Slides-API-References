---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードのスコープ内名前空間を返します。
type: docs
weight: 430
url: /ja/system.xml.xpath/xpathnavigator/getnamespacesinscope/
---
## XPathNavigator::GetNamespacesInScope(XmlNamespaceScope) メソッド


現在のノードのスコープ内名前空間を返します。

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XPath::XPathNavigator::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../../system.xml/xmlnamespacescope/) | 返す名前空間を指定する XmlNamespaceScope の値。 |

### 戻り値

プレフィックスをキーとした名前空間名の IDictionary コレクション。

## 関連項目

* Enum [XmlNamespaceScope](../../../system.xml/xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)