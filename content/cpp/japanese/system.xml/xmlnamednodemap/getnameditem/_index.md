---
title: GetNamedItem()
second_title: Aspose.Slides for C++ API リファレンス
description: 名前で指定された XmlNode を取得します。
type: docs
weight: 14
url: /ja/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) メソッド

名前で指定された[XmlNode](../../xmlnode/)を取得します。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 取得するノードの完全修飾名です。マッチするノードの[XmlNode::get_Name](../../xmlnode/get_name/)値と照合されます。 |

### 戻り値

指定された名前を持つ[XmlNode](../../xmlnode/)を返します。マッチするノードが見つからない場合は **nullptr** が返されます。

## XmlNamedNodeMap::GetNamedItem(String, String) メソッド

[XmlNode::get_LocalName](../../xmlnode/get_localname/) と [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) の値が一致するノードを取得します。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 取得するノードのローカル名です。 |
| namespaceURI | [String](../../../system/string/) | 取得するノードの名前空間 Uniform Resource Identifier (URI) です。 |

### 戻り値

ローカル名と名前空間 URI が一致する[XmlNode](../../xmlnode/)を返します。マッチするノードが見つからない場合は **nullptr** が返されます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [String](../../../system/string/)
* クラス [XmlNamedNodeMap](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)