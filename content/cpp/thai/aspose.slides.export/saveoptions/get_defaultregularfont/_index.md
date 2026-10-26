---
title: get_DefaultRegularFont()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ส่งคืนแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ อ่าน System::String."
type: docs
weight: 53
url: /th/aspose.slides.export/saveoptions/get_defaultregularfont/
---
## SaveOptions::get_DefaultRegularFont() เมธอด


ส่งคืนแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ อ่าน [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::SaveOptions::get_DefaultRegularFont() override
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