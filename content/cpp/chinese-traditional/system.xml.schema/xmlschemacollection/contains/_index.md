---
title: Contains()
second_title: Aspose.Slides for C++ API 參考
description: 傳回一個值，用來表示指定的 XmlSchema 的 targetNamespace 是否位於集合中。
type: docs
weight: 66
url: /zh-hant/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) 方法


傳回一個值，用來表示指定的 [XmlSchema](../../xmlschema/) 的 **targetNamespace** 是否位於集合中。

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) 物件。 |

### 傳回值

**true** 表示集合中有相同 **targetNamespace** 的結構描述; 否則回傳 **false**。

## XmlSchemaCollection::Contains(const String\&) 方法


傳回一個值，用來表示具有指定命名空間的結構描述是否位於集合中。

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | 與結構描述相關聯的命名空間 URI。對於 XML 結構描述，通常是目標命名空間。 |

### 傳回值

**true** 表示集合中有具有指定命名空間的結構描述; 否則回傳 **false**。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlSchema](../../xmlschema/)
* 類別 [XmlSchemaCollection](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Xml::Schema](../../)
* 函式庫 [Aspose.Slides](../../../)