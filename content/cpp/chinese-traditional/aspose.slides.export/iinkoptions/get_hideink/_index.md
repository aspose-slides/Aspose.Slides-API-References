---
title: get_HideInk()
second_title: Aspose.Slides for C++ API 參考
description: 在匯出文件中顯示或隱藏 Ink 元素。
type: docs
weight: 1
url: /zh-hant/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() 方法


在導出文件中顯示或隱藏 [Ink](../../../aspose.slides.ink/) 元素。

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## 備註


預設值為 false。 

以下範例示範如何在導出的 PDF 文件中隱藏 [Ink](../../../aspose.slides.ink/) 元素： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 參見

* 類別 [IInkOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)