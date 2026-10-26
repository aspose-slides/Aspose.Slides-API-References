---
title: get_OutputPath()
second_title: Aspose.Slides C++ API referencia
description: "Meghatározza, hogy hol kell tárolni a külső erőforrásokat. Olvassa el System::String."
type: docs
weight: 79
url: /hu/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() metódus


Meghatározza, hogy hol kell tárolni a külső erőforrásokat. Olvassa el [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
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
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)