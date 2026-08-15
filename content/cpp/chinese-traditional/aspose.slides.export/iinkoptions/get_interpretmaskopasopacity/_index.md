---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用 ROP 操作或不透明度來呈現筆刷。
type: docs
weight: 27
url: /zh-hant/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() 方法


使用 ROP 操作或不透明度來呈現筆刷。

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## 備註


預設值為 true.

以下範例示範如何使用 ROP 來匯出 [Ink](../../../aspose.slides.ink/) 元素:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 另見

* 類別 [IInkOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)