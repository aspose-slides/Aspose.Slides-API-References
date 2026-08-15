---
title: XmlSeverityType
second_title: Aspose.Slides for C++ API 參考文件
description: 表示驗證事件的嚴重程度。
type: docs
weight: 1080
url: /zh-hant/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType 列舉

表示驗證事件的嚴重程度。

```cpp
enum class XmlSeverityType
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Error | 0 | 表示在驗證實例文件時發生驗證錯誤。這適用於文件類型定義 (DTDs) 和 XML [Schema](../) 定義語言 (XSD) 綱要。World Wide [Web](../../system.web/) Consortium (W3C) 的有效性約束被視為錯誤。如果未建立驗證事件處理程序，錯誤將拋出例外。 |
| Warning | 1 | 表示發生了非錯誤的驗證事件。當沒有 DTD，或沒有 XML [Schema](../) 以對特定元素或屬性進行驗證時，通常會發出警告。與錯誤不同，如果沒有驗證事件處理程序，警告不會拋出例外。 |

## 參見

* 命名空間 [System::Xml::Schema](../)
* 函式庫 [Aspose.Slides](../../)