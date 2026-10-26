---
title: set_OutputPath()
second_title: Aspose.Slides voor C++ API Referentie
description: "Bepaalt waar externe bronnen moeten worden opgeslagen. Schrijf System::String."
type: docs
weight: 92
url: /nl/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) methode


Bepaalt waar externe bronnen moeten worden opgeslagen. Schrijf [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
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