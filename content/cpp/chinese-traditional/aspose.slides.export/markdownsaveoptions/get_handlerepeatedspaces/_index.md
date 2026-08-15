---
title: get_HandleRepeatedSpaces()
second_title: Aspose.Slides for C++ API 參考
description: 指定在 Markdown 匯出期間，應如何處理連續的普通空格字元。
type: docs
weight: 235
url: /zh-hant/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const 方法

指定在 Markdown 匯出期間，應如何處理連續的普通空格字元。

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## 備註

* 保持為普通空格字元，
* 在普通空格與不換行空格實體 (**&nbsp;**) 之間交替，
* 或在第一個之後全部替換為 **&nbsp**，以在 Markdown 輸出中保持視覺對齊。

預設值為 [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/)。

## 另見

* 列舉 [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* 類別 [MarkdownSaveOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 程式庫 [Aspose.Slides](../../../)