---
title: GetAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前の属性の値を返します。
type: docs
weight: 209
url: /ja/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) メソッド


指定された名前の属性の値を返します。

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 取得する属性の名前です。これは修飾名です。マッチするノードの **get_Name** 値と照合されます。 |

### 戻り値

指定された属性の値です。マッチする属性が見つからない場合、または属性に指定された値またはデフォルト値がない場合は空文字列が返されます。

## XmlElement::GetAttribute(String, String) メソッド


指定されたローカル名と名前空間 URI を持つ属性の値を返します。

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 取得する属性のローカル名です。 |
| namespaceURI | [String](../../../system/string/) | 取得する属性の名前空間 URI です。 |

### 戻り値

指定された属性の値です。マッチする属性が見つからない場合、または属性に指定された値またはデフォルト値がない場合は空文字列が返されます。

## 参考

* クラス [String](../../../system/string/)
* クラス [XmlElement](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)