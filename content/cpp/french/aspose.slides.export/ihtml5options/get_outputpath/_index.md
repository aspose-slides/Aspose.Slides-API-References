---
title: get_OutputPath()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Détermine où les ressources externes doivent être stockées. Lire System::String."
type: docs
weight: 79
url: /fr/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() method


Détermine où les ressources externes doivent être stockées. Lire [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
```

## Remarques


Exemple: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IHtml5Options](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)