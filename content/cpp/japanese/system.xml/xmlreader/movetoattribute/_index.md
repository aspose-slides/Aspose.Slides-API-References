---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: "派生クラスでオーバーライドされた場合、指定された XmlReader::get_Name の値を持つ属性に移動します。"
type: docs
weight: 625
url: /ja/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) メソッド


派生クラスでオーバーライドされた場合、指定された[XmlReader::get_Name](../get_name/)値を持つ属性に移動します。

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性の修飾名です。 |

### 戻り値

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## XmlReader::MoveToAttribute(String, String) メソッド


派生クラスでオーバーライドされた場合、指定された[XmlReader::get_LocalName](../get_localname/)と[XmlReader::get_NamespaceURI](../get_namespaceuri/)値を持つ属性に移動します。

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性のローカル名です。 |
| ns | [String](../../../system/string/) | 属性の名前空間URIです。 |

### 戻り値

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## XmlReader::MoveToAttribute(int32_t) メソッド


派生クラスでオーバーライドされた場合、指定されたインデックスの属性に移動します。

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| i | **int32_t** | 属性のインデックスです。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)