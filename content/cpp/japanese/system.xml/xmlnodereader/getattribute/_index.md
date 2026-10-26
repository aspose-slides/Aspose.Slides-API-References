---
title: GetAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前の属性の値を返します。
type: docs
weight: 287
url: /ja/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) メソッド

指定された名前の属性の値を返します。

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性の完全修飾名。 |

### 戻り値

指定された属性の値です。属性が見つからない場合は **nullptr** が返されます。

## XmlNodeReader::GetAttribute(String, String) メソッド

指定されたローカル名と名前空間URIを持つ属性の値を返します。

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性のローカル名。 |
| namespaceURI | [String](../../../system/string/) | 属性の名前空間URI。 |

### 戻り値

指定された属性の値です。属性が見つからない場合は **nullptr** が返されます。

## XmlNodeReader::GetAttribute(int32_t) メソッド

指定されたインデックスの属性の値を返します。

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| attributeIndex | **int32_t** | 属性のインデックス。インデックスはゼロベースです。（最初の属性のインデックスは0です。） |

### 戻り値

指定された属性の値です。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlNodeReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)