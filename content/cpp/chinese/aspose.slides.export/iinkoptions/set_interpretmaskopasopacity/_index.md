---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API 参考
description: 使用 ROP 操作或不透明度来渲染画笔。
type: docs
weight: 40
url: /zh/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) 方法


使用 ROP 操作或不透明度来渲染画笔。

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## 备注


默认值为 true。 

下面的示例演示如何使用 ROP 设置以导出 [Ink](../../../aspose.slides.ink/) 元素： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 另见

* 类 [IInkOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)