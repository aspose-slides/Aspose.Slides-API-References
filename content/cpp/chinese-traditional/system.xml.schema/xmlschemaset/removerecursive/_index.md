---
title: RemoveRecursive()
second_title: Aspose.Slides for C++ API 參考
description: 移除指定的 XML 架構定義語言 (XSD) 架構，以及它從 XmlSchemaSet 匯入的所有架構。
type: docs
weight: 183
url: /zh-hant/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) 方法

移除指定的 XML [Schema](../../) 定義語言 (XSD) 架構及其從 [XmlSchemaSet](../) 匯入的所有架構。

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | 要從 [XmlSchemaSet](../) 中移除的 [XmlSchema](../../xmlschema/) 物件。 |

### 返回值

**true** 如果成功移除 [XmlSchema](../../xmlschema/) 物件及其所有匯入的項目；否則 **false**。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlSchema](../../xmlschema/)
* 類別 [XmlSchemaSet](../)
* 命名空間 [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)