---
title: set_HandleRepeatedSpaces()
second_title: Aspose.Slides C++ API 參考
description: 指定在 Markdown 匯出期間，如何處理重複的普通空格字元。
type: docs
weight: 248
url: /zh-hant/aspose.slides.export/markdownsaveoptions/set_handlerepeatedspaces/
---
## MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces) 方法

指定在 Markdown 匯出期間，如何處理重複的普通空格字元。

```cpp
void Aspose::Slides::Export::MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces value)
```

## 備註

此屬性定義連續空格是否：
* 保持為普通空格字元，
* 在普通空格與不換行空格實體 (**&nbsp;**) 之間交替，
* 或在第一個之後全部以 **&nbsp;** 取代，以在 Markdown 輸出中保留視覺對齊。

預設值為 [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## 另請參閱

* 列舉 [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* 類別 [MarkdownSaveOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)