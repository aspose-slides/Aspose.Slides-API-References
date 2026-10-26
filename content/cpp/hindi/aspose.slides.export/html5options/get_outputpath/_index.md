---
title: get_OutputPath()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "निर्धारित करता है कि बाहरी संसाधन कहां संग्रहीत किए जाने चाहिए। पढ़ें System::String."
type: docs
weight: 79
url: /hi/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() विधि


निर्धारित करता है कि बाहरी संसाधन कहां संग्रहीत किए जाएँ। पढ़ें [System::String](../../../system/string/)।

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
```

## टिप्पणी


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## देखें भी

* क्लास [String](../../../system/string/)
* क्लास [Html5Options](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)