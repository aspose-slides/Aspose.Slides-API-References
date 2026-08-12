---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रेजेंटेशन को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना है या नहीं निर्दिष्ट करता है। लिखें bool। डिफ़ॉल्ट मान false है।
type: docs
weight: 118
url: /hi/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) विधि

निर्दिष्ट करता है कि प्रस्तुति को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ें या नहीं। लिखें **bool**. डिफ़ॉल्ट मान **false** है।

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## टिप्पणी

जब इस प्रॉपर्टी को **true** सेट किया जाता है, तो जावास्क्रिप्ट कॉल वाले हाइपरलिंक को सहेजते समय अनदेखा किया जाएगा।

जब इस प्रॉपर्टी को **false** सेट किया जाता है, तो सभी हाइपरलिंक सहेजे जाएंगे।

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## देखें भी

* वर्ग [SaveOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)