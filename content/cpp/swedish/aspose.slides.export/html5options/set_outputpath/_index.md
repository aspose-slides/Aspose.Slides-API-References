---
title: set_OutputPath()
second_title: Aspose.Slides för C++ API-referens
description: "Bestämmer var externa resurser ska lagras. Skriv System::String."
type: docs
weight: 92
url: /sv/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) metod

Bestämmer var externa resurser ska lagras. Skriv [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
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