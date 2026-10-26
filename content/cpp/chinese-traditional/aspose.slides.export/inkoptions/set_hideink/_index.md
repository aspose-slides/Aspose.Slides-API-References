---
title: set_HideInk()
second_title: Aspose.Slides for C++ API 參考
description: 顯示或隱藏匯出文件中的 Ink 元素。
type: docs
weight: 14
url: /zh-hant/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) 方法

顯示或隱藏匯出文件中的 [Ink](../../../aspose.slides.ink/) 元素。

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## 備註

預設值為 false。 

以下範例示範如何在匯出的 PDF 文件中隱藏 [Ink](../../../aspose.slides.ink/) 元素： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 另請參閱

* 類別 [InkOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)