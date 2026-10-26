---
title: RemoveAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 属性を名前で削除します。
type: docs
weight: 235
url: /ja/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) メソッド

属性を名前で削除します。

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 削除する属性の名前です。これは修飾名です。マッチングノードの **get_Name** の値と比較されます。 |

## XmlElement::RemoveAttribute(String, String) メソッド

指定されたローカル名と名前空間 URI を持つ属性を削除します。（削除された属性にデフォルト値がある場合、すぐに置き換えられます。）

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 削除する属性のローカル名です。 |
| namespaceURI | [String](../../../system/string/) | 削除する属性の名前空間 URI です。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlElement](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)