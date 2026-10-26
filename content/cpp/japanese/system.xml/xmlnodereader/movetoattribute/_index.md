---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前の属性へ移動します。
type: docs
weight: 300
url: /ja/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) メソッド

指定された名前の属性へ移動します。

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性の修飾名。 |

### 戻り値

**true** が属性が見つかった場合; それ以外の場合は **false**。**false** の場合、リーダーの位置は変わりません。

## XmlNodeReader::MoveToAttribute(String, String) メソッド

指定されたローカル名と名前空間 URI の属性へ移動します。

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性のローカル名。 |
| namespaceURI | [String](../../../system/string/) | 属性の名前空間 URI。 |

### 戻り値

**true** が属性が見つかった場合; それ以外の場合は **false**。**false** の場合、リーダーの位置は変わりません。

## XmlNodeReader::MoveToAttribute(int32_t) メソッド

指定されたインデックスの属性へ移動します。

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| attributeIndex | **int32_t** | 属性のインデックス。 |

## 関連項目

* クラス [String](../../../system/string/)
* クラス [XmlNodeReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)