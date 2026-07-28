---
title: set_OutputPath()
second_title: Aspose.Slides C++ API referencia
description: "Megállapítja, hogy hol kell tárolni a külső erőforrásokat. Írja a System::String-et."
type: docs
weight: 92
url: /hu/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) metódus


Meghatározza, hogy hol kell tárolni a külső erőforrásokat. Írja [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [Html5Options](../)
* Névterület [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)