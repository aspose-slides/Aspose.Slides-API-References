---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 將指定 URL 的 XML Schema 定義語言 (XSD) schema 新增至 XmlSchemaSet.
type: docs
weight: 157
url: /zh-hant/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) 方法

將指定 URL 的 XML [Schema](../../) 定義語言 (XSD) schema 新增至 [XmlSchemaSet](../)。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Schema 的 **targetNamespace** 值，或 **nullptr** 以使用 schema 中指定的 **targetNamespace**。 |
| schemaUri | const [String](../../../system/string/)\& | 指定要載入之 schema 的 URL。 |

### 傳回值

如果 schema 有效，則傳回 [XmlSchema](../../xmlschema/) 物件。如果 schema 無效且指定了 ValidationEventHandler，則傳回 **nullptr** 並引發適當的驗證事件。否則，會拋出 XmlSchemaException。

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) 方法

將位於 [XmlReader](../../../system.xml/xmlreader/) 中的 XML [Schema](../../) 定義語言 (XSD) schema 新增至 [XmlSchemaSet](../)。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Schema 的 **targetNamespace** 值，或 **nullptr** 以使用 schema 中指定的 **targetNamespace**。 |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 此 [XmlReader](../../../system.xml/xmlreader/) 物件。 |

### 傳回值

如果 schema 有效，則傳回 [XmlSchema](../../xmlschema/) 物件。如果 schema 無效且指定了 ValidationEventHandler，則傳回 **nullptr** 並引發適當的驗證事件。否則，會拋出 XmlSchemaException。

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) 方法

將給定 [XmlSchemaSet](../) 中的所有 XML [Schema](../../) 定義語言 (XSD) schema 新增至 [XmlSchemaSet](../)。

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | 此 [XmlSchemaSet](../) 物件。 |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) 方法

將給定的 [XmlSchema](../../xmlschema/) 新增至 [XmlSchemaSet](../)。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | 要新增至 [XmlSchemaSet](../) 的 [XmlSchema](../../xmlschema/) 物件。 |

### 傳回值

如果 schema 有效，則傳回 [XmlSchema](../../xmlschema/) 物件。如果 schema 無效且指定了 ValidationEventHandler，則傳回 **nullptr** 並引發適當的驗證事件。否則，會拋出 XmlSchemaException。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlSchema](../../xmlschema/)
* 類別 [String](../../../system/string/)
* 類別 [XmlSchemaSet](../)
* 類別 [XmlReader](../../../system.xml/xmlreader/)
* 命名空間 [System::Xml::Schema](../../)
* 函式庫 [Aspose.Slides](../../../)