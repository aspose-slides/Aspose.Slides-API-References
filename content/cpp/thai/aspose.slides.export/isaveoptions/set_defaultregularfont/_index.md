---
title: set_DefaultRegularFont()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "ตั้งค่าแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. เขียน System::String."
type: docs
weight: 66
url: /th/aspose.slides.export/isaveoptions/set_defaultregularfont/
---
## ISaveOptions::set_DefaultRegularFont(System::String) เมธอด


ตั้งค่าแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. เขียน [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_DefaultRegularFont(System::String value)=0
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
* คลาส [ISaveOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)