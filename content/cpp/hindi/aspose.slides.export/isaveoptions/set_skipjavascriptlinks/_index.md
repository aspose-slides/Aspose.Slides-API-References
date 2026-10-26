---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट करता है कि प्रस्तुति को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं। लिखें **bool**। डिफ़ॉल्ट मान **false** है।
type: docs
weight: 118
url: /hi/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) विधि


निर्दिष्ट करता है कि प्रस्तुति को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं। लिखें **bool**। डिफ़ॉल्ट मान **false** है।

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
```

## टिप्पणियाँ


जब इस प्रॉपर्टी को **true** पर सेट किया जाता है, तो जावास्क्रिप्ट कॉल वाले हाइपरलिंक सहेजते समय अनदेखा कर दिए जाएंगे।

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