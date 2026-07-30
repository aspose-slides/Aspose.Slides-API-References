---
title: get_OutputPath()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: "Určuje, kde mají být uloženy externí zdroje. Přečtěte si System::String."
type: docs
weight: 79
url: /cs/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() metoda


Určuje, kde mají být uloženy externí zdroje. Přečtěte si [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [IHtml5Options](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)