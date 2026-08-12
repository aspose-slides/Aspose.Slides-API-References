---
title: get_DefaultRegularFont()
second_title: Aspose.Slides for C++ API संदर्भ
description: "जब स्रोत फ़ॉन्ट नहीं मिलता है तो उपयोग किया जाने वाला फ़ॉन्ट लौटाता है। पढ़ता है System::String."
type: docs
weight: 53
url: /hi/aspose.slides.export/isaveoptions/get_defaultregularfont/
---
## ISaveOptions::get_DefaultRegularFont() मेथड


जब स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किया जाने वाला फ़ॉन्ट लौटाता है। पढ़ता है [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::ISaveOptions::get_DefaultRegularFont()=0
```

## टीप



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

## देखें

* क्लास [String](../../../system/string/)
* क्लास [ISaveOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)