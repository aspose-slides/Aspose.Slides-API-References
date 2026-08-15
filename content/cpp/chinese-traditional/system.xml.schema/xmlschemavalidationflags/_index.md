---
title: XmlSchemaValidationFlags
second_title: Aspose.Slides C++ API 參考
description: 指定 XmlSchemaValidator 和 XmlReader 類別使用的結構驗證選項。
type: docs
weight: 1054
url: /zh-hant/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags 列舉

指定 [XmlSchemaValidator](../xmlschemavalidator/) 與 [XmlReader](../../system.xml/xmlreader/) 類別使用的結構驗證選項。

```cpp
enum class XmlSchemaValidationFlags
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| None | 0 | 不要處理身分限制、內嵌結構、結構位置提示，或報告結構驗證警告。 |
| ProcessInlineSchema | 1 | 處理驗證過程中遇到的內嵌結構。 |
| ProcessSchemaLocation | 2 | 處理驗證過程中遇到的結構位置提示（**xsi:schemaLocation**、**xsi:noNamespaceSchemaLocation**）。 |
| ReportValidationWarnings | 4 | 報告驗證過程中遇到的結構驗證警告。 |
| ProcessIdentityConstraints | 8 | 處理驗證過程中遇到的身分限制（**xs:ID**、**xs:IDREF**、**xs:key**、**xs:keyref**、**xs:unique**）。 |
| AllowXmlAttributes | 16 | 允許 xml:* 屬性即使未在結構中定義。這些屬性將根據其資料類型進行驗證。 |

## 另請參閱

* 命名空間 [System::Xml::Schema](../)
* 函式庫 [Aspose.Slides](../../)