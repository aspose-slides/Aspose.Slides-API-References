---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前の属性へ移動します。
type: docs
weight: 456
url: /ja/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) メソッド

指定された名前の属性へ移動します。

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性の修飾済み名前。 |

### 戻り値

**true** 属性が見つかった場合; それ以外の場合は **false**。 **false** の場合、リーダーの位置は変更されません。

## XmlValidatingReader::MoveToAttribute(String, String) メソッド

指定されたローカル名と名前空間 Uniform Resource Identifier (URI) を持つ属性へ移動します。

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性のローカル名。 |
| namespaceURI | [String](../../../system/string/) | 属性の名前空間 URI。 |

### 戻り値

**true** 属性が見つかった場合; それ以外の場合は **false**。 **false** の場合、リーダーの位置は変更されません。

## XmlValidatingReader::MoveToAttribute(int32_t) メソッド

指定されたインデックスの属性へ移動します。

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| i | **int32_t** | 属性のインデックス。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlValidatingReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)