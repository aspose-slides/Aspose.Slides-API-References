---
title: get_DefaultRegularFont()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "जब स्रोत फ़ॉन्ट नहीं मिलता है तो उपयोग किया गया फ़ॉन्ट लौटाता है। System::String पढ़ता है।"
type: docs
weight: 53
url: /hi/aspose.slides.export/saveoptions/get_defaultregularfont/
---
## SaveOptions::get_DefaultRegularFont() विधि


यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किया गया फ़ॉन्ट लौटाता है। [System::String](../../../system/string/) पढ़ता है।

```cpp
System::String Aspose::Slides::Export::SaveOptions::get_DefaultRegularFont() override
```

## टिप्पणी



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

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [SaveOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)