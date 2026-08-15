---
title: Validate()
second_title: Aspose.Slides for C++ API 參考
description: "驗證 XmlDocument，使其符合包含於 XmlDocument::get_Schemas 清單中的 XML Schema Definition Language (XSD) 架構。"
type: docs
weight: 573
url: /zh-hant/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) 方法

驗證 [XmlDocument](../)，使其符合包含於 [XmlDocument::get_Schemas](../get_schemas/) 清單中的 XML [Schema](../../../system.xml.schema/) 定義語言 (XSD) 架構。

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | 接收有關結構驗證警告和錯誤資訊的 [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) 物件。 |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) 方法

驗證指定的 [XmlNode](../../xmlnode/) 物件，使其符合 [XmlDocument::get_Schemas](../get_schemas/) 清單中的 XML [Schema](../../../system.xml.schema/) 定義語言 (XSD) 架構。

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | 接收有關結構驗證警告和錯誤資訊的 [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) 物件。 |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | 用於驗證的由 [XmlDocument](../) 建立的 [XmlNode](../../xmlnode/) 物件。 |

## 參見

* 型別別名 [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlDocument](../)
* 類別 [XmlNode](../../xmlnode/)
* 名稱空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)