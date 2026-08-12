---
title: set_EmbedImages()
second_title: Aspose.Slides के लिये C++ API संदर्भ
description: छवियों को एम्बेड करने का विकल्प सेट करता है। लिखें bool.
type: docs
weight: 66
url: /hi/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) मेथड


छवियों को एम्बेड करने का विकल्प सेट करता है। लिखें **bool**।

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
```

## टिप्पणी


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## संबंधित देखें

* क्लास [Html5Options](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)