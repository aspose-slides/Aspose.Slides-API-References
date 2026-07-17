---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API 参考
description: 使用 ROP 操作或不透明度来渲染画笔。
type: docs
weight: 40
url: /zh/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) 方法


使用 ROP 操作或不透明度来渲染画笔。

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
```

## 备注


默认值为 true. 

下一个示例演示如何使用 ROP 设置导出 [Ink](../../../aspose.slides.ink/) 元素: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 另见

* 类 [InkOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)