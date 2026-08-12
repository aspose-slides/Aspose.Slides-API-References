---
title: get_OutputPath()
second_title: Aspose.Slides C++ API के लिए संदर्भ
description: "निर्धारित करता है कि बाहरी संसाधन कहाँ संग्रहीत किए जाने चाहिए। पढ़ें System::String."
type: docs
weight: 79
url: /hi/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() मेथड


निर्धारित करता है कि बाहरी संसाधन कहाँ संग्रहीत किए जाने चाहिए। पढ़ें [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
```

## टिप्पणी


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [IHtml5Options](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)