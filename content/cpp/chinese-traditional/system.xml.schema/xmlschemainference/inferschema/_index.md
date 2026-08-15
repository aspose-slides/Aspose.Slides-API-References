---
title: InferSchema()
second_title: Aspose.Slides C++ API 參考
description: 從指定的 XmlReader 物件中包含的 XML 文件推斷 XML 架構定義語言 (XSD) 架構。
type: docs
weight: 66
url: /zh-hant/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) method


從指定的 [XmlReader](../../../system.xml/xmlreader/) 物件中包含的 XML 文件推斷 XML [Schema](../../) 定義語言 (XSD) 架構。

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含欲推斷架構之 XML 文件的 [XmlReader](../../../system.xml/xmlreader/) 物件。 |

### 返回值

包含推斷出的架構之 [XmlSchemaSet](../../xmlschemaset/) 物件。

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) method


從指定的 [XmlReader](../../../system.xml/xmlreader/) 物件中包含的 XML 文件推斷 XML [Schema](../../) 定義語言 (XSD) 架構，並使用在具有相同目標命名空間的 [XmlSchemaSet](../../xmlschemaset/) 物件中現有的架構來精緻推斷出的架構。

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含欲推斷架構之 XML 文件的 [XmlReader](../../../system.xml/xmlreader/) 物件。 |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | 包含用於精緻推斷架構的現有架構之 [XmlSchemaSet](../../xmlschemaset/) 物件。 |

### 返回值

包含推斷出的架構之 [XmlSchemaSet](../../xmlschemaset/) 物件。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)