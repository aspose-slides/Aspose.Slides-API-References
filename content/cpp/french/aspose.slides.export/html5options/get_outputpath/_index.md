---
title: get_OutputPath()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Détermine où les ressources externes doivent être stockées. Lire System::String."
type: docs
weight: 79
url: /fr/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() méthode


Détermine où les ressources externes doivent être stockées. Lire [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
```

## Remarques


Exemple: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [Html5Options](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)