---
title: get_EmbedImages()
second_title: Aspose.Slides for C++ API संदर्भ
description: छवियों के एम्बेडिंग विकल्प को लौटाता है। पढ़ें bool.
type: docs
weight: 53
url: /hi/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() विधि


छवियों के एम्बेडिंग विकल्प को लौटाता है। पढ़ें **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## देखें

* क्लास [Html5Options](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)