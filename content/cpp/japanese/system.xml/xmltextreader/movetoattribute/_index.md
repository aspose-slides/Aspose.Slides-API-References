---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前の属性に移動します。
type: docs
weight: 508
url: /ja/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) メソッド


指定された名前の属性に移動します。

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性の修飾名。 |

### 戻り値

属性が見つかった場合は **true**、それ以外の場合は **false**。**false** の場合、リーダーの位置は変更されません。

## XmlTextReader::MoveToAttribute(String, String) メソッド


指定されたローカル名と名前空間URIの属性に移動します。

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性のローカル名。 |
| namespaceURI | [String](../../../system/string/) | 属性の名前空間URI。 |

### 戻り値

属性が見つかった場合は **true**、それ以外の場合は **false**。**false** の場合、リーダーの位置は変更されません。

## XmlTextReader::MoveToAttribute(int32_t) メソッド


指定されたインデックスの属性に移動します。

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| i | **int32_t** | 属性のインデックス。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlTextReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)