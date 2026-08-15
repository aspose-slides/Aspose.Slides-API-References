---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 將由給定 URL 定位的結構描述加入到結構描述集合中。
type: docs
weight: 40
url: /zh-hant/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) 方法

將由給定 URL 定位的結構描述加入到結構描述集合中。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | 與結構描述相關聯的命名空間 URI。對於 XML 結構描述，通常為 **targetNamespace**。 |
| uri | const [String](../../../system/string/)\& | 指定要載入之結構描述的 URL。 |

### 回傳值

已加入結構描述集合的 [XmlSchema](../../xmlschema/)；如果加入的結構描述是 XDR 結構描述或結構描述中有編譯錯誤，則返回 **nullptr**。

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) 方法

將包含於 [XmlReader](../../../system.xml/xmlreader/) 的結構描述加入到結構描述集合中。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | 與結構描述相關聯的命名空間 URI。對於 XML 結構描述，通常為 **targetNamespace**。 |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) 包含要加入的結構描述。 |

### 回傳值

已加入結構描述集合的 [XmlSchema](../../xmlschema/)；如果加入的結構描述是 XDR 結構描述或結構描述中有編譯錯誤，則返回 **nullptr**。

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

將包含於 [XmlReader](../../../system.xml/xmlreader/) 的結構描述加入到結構描述集合中。指定的 [XmlResolver](../../../system.xml/xmlresolver/) 用於解析任何外部資源。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | 與結構描述相關聯的命名空間 URI。對於 XML 結構描述，通常為 **targetNamespace**。 |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) 包含要加入的結構描述。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於解析 **include** 和 **import** 元素或 **x-schema** 屬性（XDR 結構描述）中引用的命名空間的 [XmlResolver](../../../system.xml/xmlresolver/)。若其為 **nullptr**，則不會解析外部參照。 |

### 回傳值

已加入結構描述集合的 [XmlSchema](../../xmlschema/)；如果加入的結構描述是 XDR 結構描述或結構描述中有編譯錯誤，則返回 **nullptr**。

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) 方法

將 [XmlSchema](../../xmlschema/) 加入集合中。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | 要加入集合的 [XmlSchema](../../xmlschema/)。 |

### 回傳值

[XmlSchema](../../xmlschema/) 物件。

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) 方法

將 [XmlSchema](../../xmlschema/) 加入集合中。指定的 [XmlResolver](../../../system.xml/xmlresolver/) 用於解析任何外部參照。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | 要加入集合的 [XmlSchema](../../xmlschema/)。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | 用於解析 **include** 和 **import** 元素中引用的命名空間的 [XmlResolver](../../../system.xml/xmlresolver/)。若其為 **nullptr**，則不會解析外部參照。 |

### 回傳值

已加入結構描述集合的 [XmlSchema](../../xmlschema/)。

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) 方法

將給定集合中定義的所有命名空間（包括其相關的結構描述）加入此集合。

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | 您想加入此集合的 [XmlSchemaCollection](../)。 |

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlSchema](../../xmlschema/)
* 類別 [String](../../../system/string/)
* 類別 [XmlSchemaCollection](../)
* 類別 [XmlReader](../../../system.xml/xmlreader/)
* 類別 [XmlResolver](../../../system.xml/xmlresolver/)
* 命名空間 [System::Xml::Schema](../../)
* 函式庫 [Aspose.Slides](../../../)