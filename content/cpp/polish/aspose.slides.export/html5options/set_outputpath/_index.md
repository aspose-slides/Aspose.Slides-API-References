---
title: set_OutputPath()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Określa, gdzie należy przechowywać zasoby zewnętrzne. Zapisz System::String."
type: docs
weight: 92
url: /pl/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) metoda

Określa, gdzie należy przechowywać zasoby zewnętrzne. Napisz [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
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

## Zobacz również

* Klasa [String](../../../system/string/)
* Klasa [Html5Options](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)