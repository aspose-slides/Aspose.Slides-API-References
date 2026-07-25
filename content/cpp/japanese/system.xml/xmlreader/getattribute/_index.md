---
title: GetAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: "派生クラスでオーバーライドされた場合、指定された XmlReader::get_Name の値を持つ属性の値を取得します。"
type: docs
weight: 599
url: /ja/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) メソッド

派生クラスでオーバーライドされた場合、指定された[XmlReader::get_Name](../get_name/)値を持つ属性の値を取得します。

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性の修飾名です。 |

### 戻り値

指定された属性の値です。属性が見つからないか、値が[String::Empty](../../../system/string/empty/)の場合、**nullptr** が返されます。

## XmlReader::GetAttribute(String, String) メソッド

派生クラスでオーバーライドされた場合、指定された[XmlReader::get_LocalName](../get_localname/)と[XmlReader::get_NamespaceURI](../get_namespaceuri/)の値を持つ属性の値を取得します。

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性のローカル名です。 |
| namespaceURI | [String](../../../system/string/) | 属性の名前空間 URI です。 |

### 戻り値

指定された属性の値です。属性が見つからないか、値が[String::Empty](../../../system/string/empty/)の場合、**nullptr** が返されます。このメソッドはリーダーを移動しません。

## XmlReader::GetAttribute(int32_t) メソッド

派生クラスでオーバーライドされた場合、指定されたインデックスを持つ属性の値を取得します。

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| i | **int32_t** | 属性のインデックスです。インデックスは 0 から始まります。（最初の属性のインデックスは 0） |

### 戻り値

指定された属性の値です。このメソッドはリーダーを移動しません。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)