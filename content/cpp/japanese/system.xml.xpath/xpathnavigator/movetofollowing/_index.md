---
title: MoveToFollowing()
second_title: Aspose.Slides for C++ API リファレンス
description: 文書順で指定されたローカル名と名前空間 URI を持つ要素に XPathNavigator を移動します。
type: docs
weight: 703
url: /ja/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) メソッド

[XPathNavigator](../) を、文書順で指定されたローカル名と名前空間 URI を持つ要素に移動します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要素のローカル名。 |
| namespaceURI | [String](../../../system/string/) | 要素の名前空間 URI。 |

### 戻り値

[XPathNavigator](../) が正常に移動した場合は **true**、それ以外の場合は **false**。

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) メソッド

[XPathNavigator](../) を、文書順で指定されたローカル名と名前空間 URI を持つ要素へ、指定された境界まで移動します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要素のローカル名。 |
| namespaceURI | [String](../../../system/string/) | 要素の名前空間 URI。 |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | [XPathNavigator](../) オブジェクトは要素の境界上に位置し、現在の [XPathNavigator](../) が次の要素を検索する際にこの境界を超えて移動しません。 |

### 戻り値

[XPathNavigator](../) が正常に移動した場合は **true**、それ以外の場合は **false**。

## XPathNavigator::MoveToFollowing(XPathNodeType) メソッド

[XPathNavigator](../) を、文書順で指定された XPathNodeType の次の要素に移動します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 要素の XPathNodeType。XPathNodeType は [XPathNodeType::Attribute](../../xpathnodetype/) または [XPathNodeType::Namespace](../../xpathnodetype/) にできません。 |

### 戻り値

[XPathNavigator](../) が正常に移動した場合は **true**、それ以外の場合は **false**。

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) メソッド

[XPathNavigator](../) を、文書順で指定された XPathNodeType の次の要素へ、指定された境界まで移動します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 要素の XPathNodeType。XPathNodeType は [XPathNodeType::Attribute](../../xpathnodetype/) または [XPathNodeType::Namespace](../../xpathnodetype/) にできません。 |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | [XPathNavigator](../) オブジェクトは要素の境界上に位置し、現在の [XPathNavigator](../) が次の要素を検索する際にこの境界を超えて移動しません。 |

### 戻り値

[XPathNavigator](../) が正常に移動した場合は **true**、それ以外の場合は **false**。

## 参照

* 列挙型 [XPathNodeType](../../xpathnodetype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)