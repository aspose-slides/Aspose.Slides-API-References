---
title: Remove()
second_title: Aspose.Slides for C++ API 參考
description: 從 XmlSchemaSet 中移除指定的 XML Schema 定義語言 (XSD) 架構。
type: docs
weight: 170
url: /zh-hant/system.xml.schema/xmlschemaset/remove/
---
## XmlSchemaSet::Remove(const SharedPtr\<XmlSchema\>\&) 方法

從 [XmlSchemaSet](../) 中移除指定的 XML [Schema](../../) 定義語言 (XSD) 架構。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Remove(const SharedPtr<XmlSchema> &schema)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | 要從 [XmlSchemaSet](../) 中移除的 [XmlSchema](../../xmlschema/) 物件。 |

### 回傳值

從 [XmlSchemaSet](../) 中移除的 [XmlSchema](../../xmlschema/) 物件；如果在 [XmlSchemaSet](../) 中未找到該架構，則返回 **nullptr**。

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlSchema](../../xmlschema/)
* 類別 [XmlSchemaSet](../)
* 命名空間 [System::Xml::Schema](../../)
* 函式庫 [Aspose.Slides](../../../)