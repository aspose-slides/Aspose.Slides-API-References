---
title: RemoveNamedItem()
second_title: Aspose.Slides for C++ API リファレンス
description: XmlNamedNodeMap からノードを削除します。
type: docs
weight: 40
url: /ja/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) メソッド

[XmlNamedNodeMap](../) からノードを削除します。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 削除するノードの修飾名。名前は一致するノードの [XmlNode::get_Name](../../xmlnode/get_name/) 値と照合されます。 |

### 戻り値

この [XmlNamedNodeMap](../) から削除された [XmlNode](../../xmlnode/)、または一致するノードが見つからなかった場合は **nullptr**。

## XmlNamedNodeMap::RemoveNamedItem(String, String) メソッド

一致する [XmlNode::get_LocalName](../../xmlnode/get_localname/) と [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) の値を持つノードを削除します。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 削除するノードのローカル名。 |
| namespaceURI | [String](../../../system/string/) | 削除するノードの名前空間 URI。 |

### 戻り値

削除された [XmlNode](../../xmlnode/)、または一致するノードが見つからなかった場合は **nullptr**。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [String](../../../system/string/)
* クラス [XmlNamedNodeMap](../)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)