---
title: get_OutputPath()
second_title: Aspose.Slides for C++ API referencia
description: "Meghatározza, hogy hol kell tárolni a külső erőforrásokat. Olvassa el a System::String-et."
type: docs
weight: 79
url: /hu/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() metódus


Meghatározza, hogy hol kell tárolni a külső erőforrásokat. Olvassa [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IHtml5Options](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)