---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides C++ API 參考
description: 使用 ROP 運算或不透明度來繪製筆刷。
type: docs
weight: 40
url: /zh-hant/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) 方法


使用 ROP 運算或不透明度來繪製筆刷。

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
```

## 備註


預設值為 true。

以下範例示範如何使用 ROP 設定以匯出 [Ink](../../../aspose.slides.ink/) 元素：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 另請參閱

* 類別 [InkOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)