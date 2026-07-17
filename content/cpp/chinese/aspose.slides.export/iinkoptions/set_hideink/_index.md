---
title: set_HideInk()
second_title: Aspose.Slides for C++ API 参考
description: 在导出文档中显示或隐藏 Ink 元素。
type: docs
weight: 14
url: /zh/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) 方法

显示或隐藏导出文档中的 [Ink](../../../aspose.slides.ink/) 元素。

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
```

## 备注

默认值为 false。

下面的示例演示了如何在导出的 PDF 文档中隐藏 [Ink](../../../aspose.slides.ink/) 元素：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 另见

* 类 [IInkOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)