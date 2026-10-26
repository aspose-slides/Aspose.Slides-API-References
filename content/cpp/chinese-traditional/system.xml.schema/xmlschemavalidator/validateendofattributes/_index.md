---
title: ValidateEndOfAttributes()
second_title: Aspose.Slides C++ API 參考
description: 驗證元素上下文中是否存在所有必需的屬性，並準備 XmlSchemaValidator 物件以驗證該元素的子內容。
type: docs
weight: 170
url: /zh-hant/system.xml.schema/xmlschemavalidator/validateendofattributes/
---
## XmlSchemaValidator::ValidateEndOfAttributes(const SharedPtr\<XmlSchemaInfo\>\&) 方法

驗證元素上下文中是否存在所有必要的屬性，並準備 [XmlSchemaValidator](../) 物件以驗證元素的子內容。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateEndOfAttributes(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 一個 [XmlSchemaInfo](../../xmlschemainfo/) 物件，其屬性在成功驗證元素上下文中所有必要屬性皆存在時被設定。此參數可以是 **nullptr**。 |

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlSchemaInfo](../../xmlschemainfo/)
* 類別 [XmlSchemaValidator](../)
* 命名空間 [System::Xml::Schema](../../)
* 程式庫 [Aspose.Slides](../../../)