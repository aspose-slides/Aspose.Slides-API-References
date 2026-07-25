---
title: ValidateText()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたテキスト文字列が現在の要素コンテキストで許可されているかを検証し、現在の要素がシンプルコンテンツを持つ場合は検証のためにテキストを蓄積します。
type: docs
weight: 183
url: /ja/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) メソッド

指定されたテキスト **string** が現在の要素コンテキストで許可されているかどうかを検証し、現在の要素がシンプルコンテンツを持つ場合は検証のためにテキストを蓄積します。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | 現在の要素コンテキストで検証するテキスト **string**。 |

## XmlSchemaValidator::ValidateText(XmlValueGetter) メソッド

指定された XmlValueGetter オブジェクトが返すテキストが現在の要素コンテキストで許可されているかどうかを検証し、現在の要素がシンプルコンテンツを持つ場合は検証のためにテキストを蓄積します。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | 属性の XML [Schema](../../) 定義言語 (XSD) 型と互換性のある型としてテキスト値を渡すために使用される XmlValueGetter コールバック。 |

## 参照

* 型定義 [XmlValueGetter](../../xmlvaluegetter/)
* クラス [String](../../../system/string/)
* クラス [XmlSchemaValidator](../)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)