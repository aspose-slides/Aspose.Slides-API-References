---
title: XmlSchemaValidationFlags
second_title: Aspose.Slides for C++ API リファレンス
description: XmlSchemaValidator と XmlReader クラスで使用されるスキーマ検証オプションを指定します。
type: docs
weight: 1054
url: /ja/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags 列挙体

[XmlSchemaValidator](../xmlschemavalidator/) と [XmlReader](../../system.xml/xmlreader/) クラスで使用されるスキーマ検証オプションを指定します。

```cpp
enum class XmlSchemaValidationFlags
```

### 値

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | アイデンティティ制約、インラインスキーマ、スキーマ位置ヒントを処理せず、スキーマ検証警告も報告しません。 |
| ProcessInlineSchema | 1 | 検証中に出会ったインラインスキーマを処理します。 |
| ProcessSchemaLocation | 2 | 検証中に出会ったスキーマ位置ヒント（**xsi:schemaLocation**、**xsi:noNamespaceSchemaLocation**）を処理します。 |
| ReportValidationWarnings | 4 | 検証中に出会ったスキーマ検証警告を報告します。 |
| ProcessIdentityConstraints | 8 | 検証中に出会ったアイデンティティ制約（**xs:ID**、**xs:IDREF**、**xs:key**、**xs:keyref**、**xs:unique**）を処理します。 |
| AllowXmlAttributes | 16 | スキーマで定義されていなくても xml:* 属性を許可します。属性はそのデータ型に基づいて検証されます。 |

## 参照

* 名前空間 [System::Xml::Schema](../)
* ライブラリ [Aspose.Slides](../../)