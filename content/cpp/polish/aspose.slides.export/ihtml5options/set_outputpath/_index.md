---
title: set_OutputPath()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Określa, gdzie należy przechowywać zasoby zewnętrzne. Zapisz System::String."
type: docs
weight: 92
url: /pl/aspose.slides.export/ihtml5options/set_outputpath/
---
## IHtml5Options::set_OutputPath(System::String) metoda


Określa, gdzie należy przechowywać zasoby zewnętrzne. Zapisz [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_OutputPath(System::String value)=0
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

## Zobacz też

* Klasa [String](../../../system/string/)
* Klasa [IHtml5Options](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)