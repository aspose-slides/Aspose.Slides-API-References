---
title: get_ValidationFlags()
second_title: Aspose.Slides for C++ API リファレンス
description: "スキーマ検証設定を示す値を返します。この設定は、スキーマを検証する XmlReader オブジェクトに適用されます（XmlReaderSettings::get_ValidationType の値は ValidationType::Schema です）。"
type: docs
weight: 378
url: /ja/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() メソッド


スキーマ検証設定を示す値を返します。この設定は、スキーマを検証する [XmlReader](../../xmlreader/) オブジェクトに適用されます（[XmlReaderSettings::get_ValidationType](../get_validationtype/) の値は [ValidationType::Schema](../../validationtype/) です）。

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```


### 戻り値

検証オプションを指定する列挙値のビット単位の組み合わせです。XmlSchemaValidationFlags::ProcessIdentityConstraints と XmlSchemaValidationFlags::AllowXmlAttributes はデフォルトで有効になっています。XmlSchemaValidationFlags::ProcessInlineSchema、XmlSchemaValidationFlags::ProcessSchemaLocation、XmlSchemaValidationFlags::ReportValidationWarnings はデフォルトで無効になっています。

## 参照

* 列挙体 [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* クラス [XmlReaderSettings](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)