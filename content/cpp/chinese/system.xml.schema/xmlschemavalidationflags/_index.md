---
title: XmlSchemaValidationFlags
second_title: Aspose.Slides C++ API 参考
description: 指定 XmlSchemaValidator 和 XmlReader 类使用的模式验证选项。
type: docs
weight: 1054
url: /zh/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags 枚举


指定 [XmlSchemaValidator](../xmlschemavalidator/) 和 [XmlReader](../../system.xml/xmlreader/) 类使用的模式验证选项。

```cpp
enum class XmlSchemaValidationFlags
```

### Values

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 不要处理标识约束、内联模式、模式位置提示，或报告模式验证警告。 |
| ProcessInlineSchema | 1 | 处理验证期间遇到的内联模式。 |
| ProcessSchemaLocation | 2 | 处理验证期间遇到的模式位置提示（**xsi:schemaLocation**，**xsi:noNamespaceSchemaLocation**）。 |
| ReportValidationWarnings | 4 | 报告验证期间遇到的模式验证警告。 |
| ProcessIdentityConstraints | 8 | 处理验证期间遇到的标识约束（**xs:ID**，**xs:IDREF**，**xs:key**，**xs:keyref**，**xs:unique**）。 |
| AllowXmlAttributes | 16 | 即使在模式中未定义，也允许 xml:* 属性。这些属性将根据其数据类型进行验证。 |

## 另请参阅

* 命名空间 [System::Xml::Schema](../)
* 库 [Aspose.Slides](../../)