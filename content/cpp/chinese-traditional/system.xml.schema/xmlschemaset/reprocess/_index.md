---
title: Reprocess()
second_title: Aspose.Slides for C++ API 參考文件
description: 重新處理已存在於 XmlSchemaSet 中的 XML Schema 定義語言 (XSD) 架構。
type: docs
weight: 222
url: /zh-hant/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) 方法


重新處理已存在於 [XmlSchemaSet](../) 中的 XML [Schema](../../) 定義語言 (XSD) 架構。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | 要重新處理的 schema。 |

### 返回值

如果 schema 為有效的 schema，則返回一個 [XmlSchema](../../xmlschema/) 物件。如果 schema 無效且指定了 ValidationEventHandler，則返回 **nullptr**，並引發相應的驗證事件。否則，將拋出 XmlSchemaException。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlSchema](../../xmlschema/)
* 類別 [XmlSchemaSet](../)
* 命名空間 [System::Xml::Schema](../../)
* 函式庫 [Aspose.Slides](../../../)