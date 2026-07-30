---
title: set_OutputPath()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Určuje, kde by měly být uloženy externí zdroje. Zapište System::String."
type: docs
weight: 92
url: /cs/aspose.slides.export/ihtml5options/set_outputpath/
---
## IHtml5Options::set_OutputPath(System::String) metoda


Určuje, kde by měly být uloženy externí zdroje. Zapište [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_OutputPath(System::String value)=0
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