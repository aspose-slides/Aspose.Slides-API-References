---
title: ValidateWhitespace()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列内の空白が現在の要素コンテキストで許可されているかを検証し、現在の要素が単純コンテンツを持つ場合は検証のために空白を蓄積します。
type: docs
weight: 196
url: /ja/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) メソッド

指定された **string** の空白が現在の要素コンテキストで許可されているかを検証し、現在の要素が単純コンテンツを持つ場合は検証のために空白を蓄積します。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | 現在の要素コンテキストで検証するための空白 **string** 。 |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) メソッド

指定された XmlValueGetter オブジェクトが返す空白が現在の要素コンテキストで許可されているかを検証し、現在の要素が単純コンテンツを持つ場合は検証のために空白を蓄積します。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | 属性の XML [Schema](../../) 定義言語 (XSD) 型と互換性のある型として空白値を渡すために使用される XmlValueGetter コールバック。 |

## 参照

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [String](../../../system/string/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)