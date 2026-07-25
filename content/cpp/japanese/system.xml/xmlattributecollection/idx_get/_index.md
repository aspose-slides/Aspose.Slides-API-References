---
title: idx_get()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスの属性を返します。
type: docs
weight: 1
url: /ja/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) メソッド


指定されたインデックスの属性を返します。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| i | **int32_t** | 指定された属性のインデックスです。 |

### 戻り値

指定されたインデックスの属性です。

## XmlAttributeCollection::idx_get(const String\&) メソッド


指定された名前の属性を返します。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 属性の修飾名です。 |

### 戻り値

指定された名前の属性です。属性が存在しない場合、このメソッドは **nullptr** を返します。

## XmlAttributeCollection::idx_get(const String\&, const String\&) メソッド


指定されたローカル名と名前空間の Uniform Resource Identifier (URI) を持つ属性を返します。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 属性のローカル名です。 |
| namespaceURI | const [String](../../../system/string/)\& | 属性の名前空間 URI です。 |

### 戻り値

指定されたローカル名と名前空間 URI の属性です。属性が存在しない場合、このメソッドは **nullptr** を返します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlAttribute](../../xmlattribute/)
* クラス [XmlAttributeCollection](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)