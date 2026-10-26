---
title: get_OutputPath()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: "Określa, gdzie powinny być przechowywane zasoby zewnętrzne. Przeczytaj System::String."
type: docs
weight: 79
url: /pl/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() metoda


Określa, gdzie powinny być przechowywane zasoby zewnętrzne. Przeczytaj [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IHtml5Options](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)