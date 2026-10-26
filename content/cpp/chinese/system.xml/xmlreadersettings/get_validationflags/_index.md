---
title: get_ValidationFlags()
second_title: Aspose.Slides C++ API 参考
description: "返回一个指示模式验证设置的值。此设置适用于验证模式的 XmlReader 对象（XmlReaderSettings::get_ValidationType 值为 ValidationType::Schema）。"
type: docs
weight: 378
url: /zh/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() 方法


返回一个指示模式验证设置的值。此设置适用于验证模式的 [XmlReader](../../xmlreader/) 对象（[XmlReaderSettings::get_ValidationType](../get_validationtype/) 值为 [ValidationType::Schema](../../validationtype/)）。

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```


### 返回值

一个按位组合的枚举值，用于指定验证选项。XmlSchemaValidationFlags::ProcessIdentityConstraints 和 XmlSchemaValidationFlags::AllowXmlAttributes 默认启用。XmlSchemaValidationFlags::ProcessInlineSchema、XmlSchemaValidationFlags::ProcessSchemaLocation 和 XmlSchemaValidationFlags::ReportValidationWarnings 默认禁用。

## 另请参见

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* 类 [XmlReaderSettings](../)
* 命名空间 [System::Xml](../../)
* Library [Aspose.Slides](../../../)