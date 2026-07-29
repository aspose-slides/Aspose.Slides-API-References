---
title: get_OutputPath()
second_title: Aspose.Slides för C++ API-referens
description: "Bestämmer var externa resurser ska lagras. Läs System::String."
type: docs
weight: 79
url: /sv/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() metod


Bestämmer var externa resurser ska lagras. Läs [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Se även

* klass [String](../../../system/string/)
* klass [IHtml5Options](../)
* namnrymd [Aspose::Slides::Export](../../)
* bibliotek [Aspose.Slides](../../../)