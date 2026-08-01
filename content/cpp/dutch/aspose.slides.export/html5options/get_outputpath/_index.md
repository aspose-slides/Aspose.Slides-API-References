---
title: get_OutputPath()
second_title: Aspose.Slides voor C++ API-referentie
description: "Bepaalt waar externe bronnen moeten worden opgeslagen. Lees System::String."
type: docs
weight: 79
url: /nl/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() methode


Bepaalt waar externe bronnen moeten worden opgeslagen. Lees [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [Html5Options](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)