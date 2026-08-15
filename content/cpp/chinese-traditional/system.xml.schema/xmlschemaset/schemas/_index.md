---
title: Schemas()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回 XmlSchemaSet 中所有 XML Schema 定義語言 (XSD) 綱要的集合。
type: docs
weight: 248
url: /zh-hant/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() 方法

傳回在 [XmlSchemaSet](../) 中的所有 XML [Schema](../../) 定義語言 (XSD) 綱要的集合。

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```

### 返回值

一個 IList 物件，包含已加入 [XmlSchemaSet](../) 的所有綱要。如果未將任何綱要加入 [XmlSchemaSet](../)，則傳回空集合。

## XmlSchemaSet::Schemas(String) 方法

傳回在 [XmlSchemaSet](../) 中屬於給定命名空間的所有 XML [Schema](../../) 定義語言 (XSD) 綱要的集合。

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | 綱要的 **targetNamespace** 屬性。 |

### 返回值

一個 IList 物件，包含已加入 [XmlSchemaSet](../) 且屬於給定命名空間的所有綱要。如果未將任何綱要加入 [XmlSchemaSet](../)，則傳回空集合。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IList](../../../system.collections.generic/ilist/)
* 類別 [XmlSchema](../../xmlschema/)
* 類別 [XmlSchemaSet](../)
* 類別 [List](../../../system.collections.generic/list/)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)