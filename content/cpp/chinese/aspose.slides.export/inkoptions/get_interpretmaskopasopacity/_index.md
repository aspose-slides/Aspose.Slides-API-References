---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API 参考
description: 使用 ROP 操作或不透明度来渲染画笔。
type: docs
weight: 27
url: /zh/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() 方法


使用 ROP 操作或 Opacity 来渲染画笔。

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
```

## 备注


默认值为 true。 

下面的示例演示如何使用 ROP 来设置导出 [Ink](../../../aspose.slides.ink/) 元素： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 另请参阅

* 类 [InkOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)