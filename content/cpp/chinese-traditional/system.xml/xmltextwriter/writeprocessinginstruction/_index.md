---
title: WriteProcessingInstruction()
second_title: Aspose.Slides for C++ API 參考
description: "將處理指令寫出，名稱與文字之間保留空格，如下所示： <?name text?>。"
type: docs
weight: 326
url: /zh-hant/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) 方法

將處理指令寫出，名稱與文字之間保留空格，如下所示： **<?name text?>**。

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 處理指令的名稱。 |
| text | [String](../../../system/string/) | 要包含在處理指令中的 [Text](../../../system.text/)。 |

## 備註

此方法在 [XmlTextWriter::WriteStartDocument](../writestartdocument/) 已被呼叫之後，用於建立 XML 宣告。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlTextWriter](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)