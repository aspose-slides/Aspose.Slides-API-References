---
title: GetBuiltInSimpleType()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回一個 XmlSchemaSimpleType，該物件表示由限定名稱指定的簡單型別的內建簡單型別。
type: docs
weight: 183
url: /zh-hant/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) 方法

傳回一個 [XmlSchemaSimpleType](../../xmlschemasimpletype/)，它表示由限定名稱指定的簡單型別的內建簡單型別。

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | 簡單型別的 [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)。 |

### 返回值

代表內建簡單型別的 [XmlSchemaSimpleType](../../xmlschemasimpletype/)。

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) 方法

傳回一個 [XmlSchemaSimpleType](../../xmlschemasimpletype/)，它表示指定的簡單型別的內建簡單型別。

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | 表示簡單型別的 XmlTypeCode 值之一。 |

### 返回值

代表內建簡單型別的 [XmlSchemaSimpleType](../../xmlschemasimpletype/)。

## 另見

* 列舉 [XmlTypeCode](../../xmltypecode/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* 類別 [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* 類別 [XmlSchemaType](../)
* 命名空間 [System::Xml::Schema](../../)
* 函式庫 [Aspose.Slides](../../../)