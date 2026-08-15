---
title: Contains()
second_title: Aspose.Slides for C++ API 參考
description: 指示具有指定目標命名空間 URI 的 XML Schema 定義語言 (XSD) 結構描述是否位於 XmlSchemaSet 中。
type: docs
weight: 196
url: /zh-hant/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) 方法

指示具有指定目標命名空間 URI 的 XML [Schema](../../) 定義語言 (XSD) 結構描述是否位於 [XmlSchemaSet](../) 中。

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | 模式 **targetNamespace** 屬性。 |

### 回傳值

如果具有指定目標命名空間 URI 的結構描述位於 [XmlSchemaSet](../) 中，則返回 **true**；否則返回 **false**。

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) 方法

指示指定的 XML [Schema](../../) 定義語言 (XSD) [XmlSchema](../../xmlschema/) 物件是否位於 [XmlSchemaSet](../) 中。

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) 物件。 |

### 回傳值

如果 [XmlSchema](../../xmlschema/) 物件位於 [XmlSchemaSet](../) 中，則返回 **true**；否則返回 **false**。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [XmlSchemaSet](../)
* 類別 [XmlSchema](../../xmlschema/)
* 命名空間 [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)