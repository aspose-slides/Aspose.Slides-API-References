---
title: GetAttributeNode()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前を持つ XmlAttribute を返します。
type: docs
weight: 248
url: /ja/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) メソッド

指定された名前を持つ [XmlAttribute](../../xmlattribute/) を返します。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 取得する属性の名前です。これは修飾名です。マッチするノードの **get_Name** 値と照合されます。 |

### 戻り値

マッチする属性が見つからなかった場合は **nullptr**、それ以外の場合は指定された [XmlAttribute](../../xmlattribute/) を返します。

## XmlElement::GetAttributeNode(String, String) メソッド

指定されたローカル名および名前空間 URI を持つ [XmlAttribute](../../xmlattribute/) を返します。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性のローカル名です。 |
| namespaceURI | [String](../../../system/string/) | 属性の名前空間 URI です。 |

### 戻り値

マッチする属性が見つからなかった場合は **nullptr**、それ以外の場合は指定された [XmlAttribute](../../xmlattribute/) を返します。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlAttribute](../../xmlattribute/)
* クラス [String](../../../system/string/)
* クラス [XmlElement](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)