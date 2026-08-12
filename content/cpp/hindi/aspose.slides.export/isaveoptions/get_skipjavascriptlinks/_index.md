---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides C++ के लिए API रेफ़रेंस
description: प्रस्तुति को सहेजते समय JavaScript कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, यह निर्दिष्ट करता है। पढ़ें bool। डिफ़ॉल्ट मान false है।
type: docs
weight: 105
url: /hi/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() विधि

प्रस्तुति को सहेजते समय JavaScript कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, यह निर्दिष्ट करता है। पढ़ें **bool**। डिफ़ॉल्ट मान **false** है।

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## टिप्पणियाँ

जब इस प्रॉपर्टी को **true** पर सेट किया जाता है, तो सहेजते समय JavaScript कॉल वाले हाइपरलिंक को अनदेखा किया जाएगा।

जब इस प्रॉपर्टी को **false** पर सेट किया जाता है, तो सभी हाइपरलिंक सहेजे जाएंगे।

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## संबंधित देखें

* क्लास [ISaveOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)