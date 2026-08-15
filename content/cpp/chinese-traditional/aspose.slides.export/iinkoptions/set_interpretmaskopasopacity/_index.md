---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用 ROP 操作或不透明度來繪製筆刷。
type: docs
weight: 40
url: /zh-hant/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) 方法


使用 ROP 操作或不透明度來繪製筆刷。

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## 備註


預設值為 true。 

下一個範例示範如何使用 ROP 來設定匯出 [Ink](../../../aspose.slides.ink/) 元素： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 另請參閱

* 類別 [IInkOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 程式庫 [Aspose.Slides](../../../)