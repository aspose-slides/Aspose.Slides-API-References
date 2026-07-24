---
title: set_OutputPath()
second_title: Aspose.Slides für C++ API-Referenz
description: "Bestimmt, wo externe Ressourcen gespeichert werden sollen. Schreiben System::String."
type: docs
weight: 92
url: /de/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) Methode


Bestimmt, wo externe Ressourcen gespeichert werden sollen. Schreiben [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
```

## Bemerkungen


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [Html5Options](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)