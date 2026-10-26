---
title: set_EmbedImages()
second_title: Aspose.Slides for C++ API संदर्भ
description: छवियों को एम्बेड करने का विकल्प सेट करता है। लिखें bool.
type: docs
weight: 66
url: /hi/aspose.slides.export/ihtml5options/set_embedimages/
---
## IHtml5Options::set_EmbedImages(bool) विधि


छवियों को एम्बेड करने का विकल्प सेट करता है। लिखें **bool**।

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_EmbedImages(bool value)=0
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

* वर्ग [IHtml5Options](../)
* नामस्थान [Aspose::Slides::Export](../../)
* पुस्तकालय [Aspose.Slides](../../../)