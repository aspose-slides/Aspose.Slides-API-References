---
title: get_OutputPath()
second_title: Aspose.Slides för C++ API-referens
description: "Bestämmer var externa resurser ska lagras. Läs System::String."
type: docs
weight: 79
url: /sv/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() method


Bestämmer var externa resurser ska lagras. Läs [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Se även

* Klass [String](../../../system/string/)
* Klass [Html5Options](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)