---
title: HasAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードが指定された名前の属性を持つかどうかを判断します。
type: docs
weight: 300
url: /ja/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) メソッド

現在のノードが指定された名前の属性を持つかどうかを判断します。

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 検索する属性の名前です。これは修飾名です。一致するノードの **get_Name** の値と照合されます。 |

### 戻り値

**true** が現在のノードに指定された属性がある場合、それ以外は **false**。

## XmlElement::HasAttribute(String, String) メソッド

現在のノードが指定されたローカル名と名前空間URIの属性を持つかどうかを判断します。

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 検索する属性のローカル名です。 |
| namespaceURI | [String](../../../system/string/) | 検索する属性の名前空間URIです。 |

### 戻り値

**true** が現在のノードに指定された属性がある場合、それ以外は **false**。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlElement](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)