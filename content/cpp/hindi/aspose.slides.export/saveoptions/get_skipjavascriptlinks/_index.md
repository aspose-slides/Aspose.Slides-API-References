---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रस्तुति को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना है या नहीं, यह निर्धारित करता है। पढ़ें bool। डिफ़ॉल्ट मान false है।
type: docs
weight: 105
url: /hi/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() विधि


जब प्रस्तुति सहेजी जा रही हो, तो जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना है या नहीं, यह निर्धारित करता है। पढ़ें **bool**। डिफ़ॉल्ट मान **false** है।

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## टिप्पणियाँ


जब यह प्रॉपर्टी **true** पर सेट की जाती है, तो सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को नज़रअंदाज़ किया जाएगा।

जब यह प्रॉपर्टी **false** पर सेट की जाती है, तो सभी हाइपरलिंक्स सहेजे जाएंगे।

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## देखें

* क्लास [SaveOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)