---
title: SelectChildren()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードの子ノードのうち、指定されたXPathNodeTypeと一致するすべてのノードを選択します。
type: docs
weight: 833
url: /ja/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) メソッド

現在のノードの子ノードのうち、指定された XPathNodeType に一致するすべてのノードを選択します。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 子ノードの XPathNodeType。 |

### 戻り値

選択されたノードを含む [XPathNodeIterator](../../xpathnodeiterator/)。

## XPathNavigator::SelectChildren(String, String) メソッド

現在のノードの子ノードのうち、指定されたローカル名と名前空間 URI を持つすべてのノードを選択します。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 子ノードのローカル名。 |
| namespaceURI | [String](../../../system/string/) | 子ノードの名前空間 URI。 |

### 戻り値

選択されたノードを含む [XPathNodeIterator](../../xpathnodeiterator/)。

## 参照

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)