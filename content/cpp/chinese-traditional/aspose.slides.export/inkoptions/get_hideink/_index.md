---
title: get_HideInk()
second_title: Aspose.Slides for C++ API 參考文件
description: 在匯出文件中顯示或隱藏 Ink 元素。
type: docs
weight: 1
url: /zh-hant/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() 方法


在匯出文件中顯示或隱藏 [Ink](../../../aspose.slides.ink/) 元素。

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## 備註


預設值為 false。 

以下示例說明如何在匯出 PDF 文件中隱藏 [Ink](../../../aspose.slides.ink/) 元素： 
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