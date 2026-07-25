---
title: GetAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前を持つ属性の値を返します。
type: docs
weight: 443
url: /ja/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) メソッド

指定された名前を持つ属性の値を返します。

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性の完全修飾名です。 |

### 戻り値

指定された属性の値です。属性が見つからない場合、**nullptr** が返されます。

## XmlValidatingReader::GetAttribute(String, String) メソッド

指定されたローカル名と名前空間の Uniform Resource Identifier (URI) を持つ属性の値を返します。

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性のローカル名です。 |
| namespaceURI | [String](../../../system/string/) | 属性の名前空間 URI です。 |

### 戻り値

指定された属性の値です。属性が見つからない場合、**nullptr** が返されます。このメソッドはリーダーを移動しません。

## XmlValidatingReader::GetAttribute(int32_t) メソッド

指定されたインデックスを持つ属性の値を返します。

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| i | **int32_t** | 属性のインデックスです。インデックスは 0 ベースです。(最初の属性のインデックスは 0 です。) |

### 戻り値

指定された属性の値です。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlValidatingReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)