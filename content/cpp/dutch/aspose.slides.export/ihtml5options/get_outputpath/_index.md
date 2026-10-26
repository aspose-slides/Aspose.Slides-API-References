---
title: get_OutputPath()
second_title: Aspose.Slides voor C++ API-referentie
description: "Bepaalt waar externe bronnen moeten worden opgeslagen. Lees System::String."
type: docs
weight: 79
url: /nl/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() method

Bepaalt waar externe bronnen moeten worden opgeslagen. Lees [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
```

## Opmerkingen

Voorbeeld:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [IHtml5Options](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)