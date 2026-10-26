---
title: get_OutputPath()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Określa, gdzie należy przechowywać zasoby zewnętrzne. Przeczytaj System::String."
type: docs
weight: 79
url: /pl/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() metoda

Określa, gdzie należy przechowywać zasoby zewnętrzne. Przeczytaj [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
```

## Uwagi

Przykład:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [Html5Options](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)