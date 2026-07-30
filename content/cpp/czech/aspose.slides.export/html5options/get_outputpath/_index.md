---
title: get_OutputPath()
second_title: Aspose.Slides pro C++ API Reference
description: "Určuje, kde by měly být uloženy externí zdroje. Přečtěte si System::String."
type: docs
weight: 79
url: /cs/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() metoda

Určuje, kde by měly být uloženy externí zdroje. Přečtěte si [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
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
* Obor názvů [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)