---
title: idx_get()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前空間 URI に関連付けられた XmlSchema を返します。
type: docs
weight: 53
url: /ja/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) メソッド

Returns the [XmlSchema](../../xmlschema/) associated with the given namespace URI.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | 返したいスキーマに関連付けられた名前空間 URI。通常はスキーマの **targetNamespace** です。 |

### 戻り値

[XmlSchema](../../xmlschema/) は名前空間 URI に関連付けられます。**nullptr** は、指定された名前空間に関連付けられたロード済みスキーマが存在しない場合、または名前空間が XDR スキーマに関連付けられている場合に返されます。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlSchema](../../xmlschema/)
* クラス [String](../../../system/string/)
* クラス [XmlSchemaCollection](../)
* 名前空間 [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)