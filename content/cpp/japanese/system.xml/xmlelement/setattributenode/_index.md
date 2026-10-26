---
title: SetAttributeNode()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された XmlAttribute を追加します。
type: docs
weight: 261
url: /ja/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) method


指定された[XmlAttribute](../../xmlattribute/)を追加します。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | この要素の属性コレクションに追加する[XmlAttribute](../../xmlattribute/)ノード。 |

### 戻り値

属性が同名の既存属性を置き換える場合、古い[XmlAttribute](../../xmlattribute/)が返されます。そうでない場合は**nullptr**が返されます。

## XmlElement::SetAttributeNode(String, String) method


指定された[XmlAttribute](../../xmlattribute/)を追加します。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性のローカル名。 |
| namespaceURI | [String](../../../system/string/) | 属性の名前空間URI。 |

### 戻り値

追加する[XmlAttribute](../../xmlattribute/)。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)