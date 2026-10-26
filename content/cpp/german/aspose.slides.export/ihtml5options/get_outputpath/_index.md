---
title: get_OutputPath()
second_title: Aspose.Slides für C++ API-Referenz
description: "Bestimmt, wo externe Ressourcen gespeichert werden sollen. Lesen Sie System::String."
type: docs
weight: 79
url: /de/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() Methode


Bestimmt, wo externe Ressourcen gespeichert werden sollen. Lesen Sie [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
```

## Hinweise


Beispiel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [IHtml5Options](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)