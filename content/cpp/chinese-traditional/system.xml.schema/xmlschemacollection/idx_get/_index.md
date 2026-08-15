---
title: idx_get()
second_title: Aspose.Slides C++ API 參考文件
description: 返回與給定命名空間 URI 相關聯的 XmlSchema。
type: docs
weight: 53
url: /zh-hant/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) method

返回與給定命名空間 URI 相關聯的 [XmlSchema](../../xmlschema/)。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | 與您想返回的結構描述相關的命名空間 URI。通常會是該結構描述的 **targetNamespace**。 |

### 返回值

與該命名空間 URI 相關聯的 [XmlSchema](../../xmlschema/)；如果沒有載入與給定命名空間相關聯的結構描述，或該命名空間與 XDR 結構描述相關聯，則為 **nullptr**。

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlSchema](../../xmlschema/)
* 類別 [String](../../../system/string/)
* 類別 [XmlSchemaCollection](../)
* 命名空間 [System::Xml::Schema](../../)
* 函式庫 [Aspose.Slides](../../../)