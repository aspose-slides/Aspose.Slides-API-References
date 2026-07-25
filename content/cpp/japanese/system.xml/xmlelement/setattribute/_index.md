---
title: SetAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前の属性の値を設定します。
type: docs
weight: 222
url: /ja/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) メソッド

指定された名前の属性の値を設定します。

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 作成または変更する属性の名前です。これは修飾名です。名前にコロンが含まれる場合、プレフィックスとローカル名のコンポーネントに分割されます。 |
| value | [String](../../../system/string/) | 属性に設定する値です。 |

## XmlElement::SetAttribute(String, String, String) メソッド

指定されたローカル名と名前空間 URI の属性の値を設定します。

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性のローカル名です。 |
| namespaceURI | [String](../../../system/string/) | 属性の名前空間 URI です。 |
| value | [String](../../../system/string/) | 属性に設定する値です。 |

### 戻り値

属性の値です。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlElement](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)