---
title: set_DefaultRegularFont()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "กำหนดแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. เขียน System::String."
type: docs
weight: 66
url: /th/aspose.slides.export/saveoptions/set_defaultregularfont/
---
## SaveOptions::set_DefaultRegularFont(System::String) เมธอด


กำหนดแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. เขียน [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::SaveOptions::set_DefaultRegularFont(System::String value) override
```

## หมายเหตุ



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto htmlOpts = System::MakeObject<HtmlOptions>();
htmlOpts->set_DefaultRegularFont(u"Arial Black");
pres->Save(u"SomePresentation-out-ArialBlack.html", Aspose::Slides::Export::SaveFormat::Html, htmlOpts);
htmlOpts->set_DefaultRegularFont(u"Lucida Console");
pres->Save(u"Somepresentation-out-LucidaConsole.html", Aspose::Slides::Export::SaveFormat::Html, htmlOpts);

auto pdfOpts = System::MakeObject<PdfOptions>();
pdfOpts->set_DefaultRegularFont(u"Arial Black");
pres->Save(u"SomePresentation-out-ArialBlack.pdf", Aspose::Slides::Export::SaveFormat::Pdf, pdfOpts);
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [SaveOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)