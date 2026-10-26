---
title: CheckValidity()
second_title: Aspose.Slides for C++ API 參考文件
description: 驗證 XPathNavigator 中的 XML 資料符合所提供的 XML Schema 定義語言 (XSD) 架構。
type: docs
weight: 755
url: /zh-hant/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) 方法

驗證 [XPathNavigator](../) 中的 XML 資料符合所提供的 XML [Schema](../../../system.xml.schema/) 定義語言 (XSD) 架構。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | 包含用於驗證 [XPathNavigator](../) 中 XML 資料之結構描述的 XmlSchemaSet。 |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | 接收有關結構描述驗證警告與錯誤資訊的 ValidationEventHandler。 |

### 返回值

**true** 若未發生結構描述驗證錯誤；否則為 **false**。

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類型定義 [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* 類別 [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)