---
title: get_HideInk()
second_title: Aspose.Slides C++ API 参考
description: 在导出文档中显示或隐藏 Ink 元素。
type: docs
weight: 1
url: /zh/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() 方法

显示或隐藏 [Ink](../../../aspose.slides.ink/) 元素在导出文档中。

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## 备注

默认值为 false。 

下面的示例演示如何在导出的 PDF 文档中隐藏 [Ink](../../../aspose.slides.ink/) 元素： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 另请参阅

* 类 [IInkOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)