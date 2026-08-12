---
title: get_EmbedImages()
second_title: Aspose.Slides C++ API संदर्भ
description: छवियों को एम्बेड करने का विकल्प लौटाता है। पढ़ें bool.
type: docs
weight: 53
url: /hi/aspose.slides.export/ihtml5options/get_embedimages/
---
## IHtml5Options::get_EmbedImages() विधि

छवियों को एम्बेड करने का विकल्प लौटाता है। पढ़ें **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_EmbedImages()=0
```

## टिप्पणी


उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## देखें

* क्लास [IHtml5Options](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)