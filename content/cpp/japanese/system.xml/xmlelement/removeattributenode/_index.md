---
title: RemoveAttributeNode()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された XmlAttribute を削除します。
type: docs
weight: 274
url: /ja/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) メソッド

指定された[XmlAttribute](../../xmlattribute/)を削除します。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | 削除する[XmlAttribute](../../xmlattribute/)ノードです。削除された属性にデフォルト値がある場合、直ちに置き換えられます。 |

### 戻り値

削除された[XmlAttribute](../../xmlattribute/)、**oldAttr**が[XmlElement](../)の属性ノードでない場合は**nullptr**です。

## XmlElement::RemoveAttributeNode(String, String) メソッド

ローカル名と名前空間URIで指定された[XmlAttribute](../../xmlattribute/)を削除します。（削除された属性にデフォルト値がある場合、直ちに置き換えられます）

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性のローカル名です。 |
| namespaceURI | [String](../../../system/string/) | 属性の名前空間URIです。 |

### 戻り値

削除された[XmlAttribute](../../xmlattribute/)、[XmlElement](../)に一致する属性ノードがない場合は**nullptr**です。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlAttribute](../../xmlattribute/)
* クラス [XmlElement](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)