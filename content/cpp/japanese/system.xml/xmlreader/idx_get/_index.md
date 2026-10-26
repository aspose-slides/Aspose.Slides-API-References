---
title: idx_get()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、指定されたインデックスの属性の値を取得します。
type: docs
weight: 612
url: /ja/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) メソッド

派生クラスでオーバーライドされた場合、指定されたインデックスの属性の値を取得します。

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| i | **int32_t** | 属性のインデックスです。 |

### 戻り値

指定された属性の値です。

## XmlReader::idx_get(String) メソッド

派生クラスでオーバーライドされた場合、指定された[XmlReader::get_Name](../get_name/)値の属性の値を取得します。

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性の修飾名です。 |

### 戻り値

指定された属性の値です。属性が見つからない場合、**nullptr** が返されます。

## XmlReader::idx_get(String, String) メソッド

派生クラスでオーバーライドされた場合、指定された[XmlReader::get_LocalName](../get_localname/)および[XmlReader::get_NamespaceURI](../get_namespaceuri/)値の属性の値を取得します。

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性のローカル名です。 |
| namespaceURI | [String](../../../system/string/) | 属性の名前空間URIです。 |

### 戻り値

指定された属性の値です。属性が見つからない場合、**nullptr** が返されます。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)