---
title: get_ValidationFlags()
second_title: Aspose.Slides for C++ API 參考文件
description: "返回指示結構驗證設定的值。此設定套用於驗證結構的 XmlReader 物件（XmlReaderSettings::get_ValidationType 值為 ValidationType::Schema）。"
type: docs
weight: 378
url: /zh-hant/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() 方法


傳回指示結構驗證設定的值。此設定套用於驗證結構的 [XmlReader](../../xmlreader/) 物件（[XmlReaderSettings::get_ValidationType](../get_validationtype/) 值為 [ValidationType::Schema](../../validationtype/)）。

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```


### 回傳值

列舉值的位元組合，用來指定驗證選項。XmlSchemaValidationFlags::ProcessIdentityConstraints 與 XmlSchemaValidationFlags::AllowXmlAttributes 於預設情況下已啟用。XmlSchemaValidationFlags::ProcessInlineSchema、XmlSchemaValidationFlags::ProcessSchemaLocation 與 XmlSchemaValidationFlags::ReportValidationWarnings 於預設情況下已停用。

## 另請參閱

* 列舉 [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* 類別 [XmlReaderSettings](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)