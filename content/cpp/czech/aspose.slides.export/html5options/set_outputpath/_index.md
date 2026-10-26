---
title: set_OutputPath()
second_title: Aspose.Slides pro C++ API Reference
description: "Určuje, kde mají být uloženy externí zdroje. Zapište System::String."
type: docs
weight: 92
url: /cs/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) metoda


Určuje, kde mají být uloženy externí zdroje. Write [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [Html5Options](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)