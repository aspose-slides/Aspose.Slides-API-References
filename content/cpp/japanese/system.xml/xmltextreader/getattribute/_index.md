---
title: GetAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前を持つ属性の値を返します。
type: docs
weight: 495
url: /ja/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) メソッド

指定された名前を持つ属性の値を返します。

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性の修飾名。 |

### 戻り値

指定された属性の値を返します。属性が見つからない場合、**nullptr** が返されます。

## XmlTextReader::GetAttribute(String, String) メソッド

指定されたローカル名と名前空間 URI を持つ属性の値を返します。

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性のローカル名。 |
| namespaceURI | [String](../../../system/string/) | 属性の名前空間 URI。 |

### 戻り値

指定された属性の値を返します。属性が見つからない場合、**nullptr** が返されます。このメソッドはリーダーを移動しません。

## XmlTextReader::GetAttribute(int32_t) メソッド

指定されたインデックスを持つ属性の値を返します。

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | 属性のインデックス。インデックスはゼロベースです。（最初の属性のインデックスは 0 です。） |

### 戻り値

指定された属性の値を返します。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlTextReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)