---
title: set_DefaultRegularFont()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "यदि स्रोत फ़ॉन्ट नहीं मिलता है तो उपयोग किए जाने वाले फ़ॉन्ट को सेट करता है। System::String लिखता है।"
type: docs
weight: 66
url: /hi/aspose.slides.export/isaveoptions/set_defaultregularfont/
---
## ISaveOptions::set_DefaultRegularFont(System::String) विधि


यदि स्रोत फ़ॉन्ट नहीं मिलता है तो उपयोग किए जाने वाले फ़ॉन्ट को सेट करता है। [System::String](../../../system/string/) लिखता है।

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_DefaultRegularFont(System::String value)=0
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

## देखें

* वर्ग [String](../../../system/string/)
* वर्ग [ISaveOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)