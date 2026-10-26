---
title: set_OutputPath()
second_title: Aspose.Slides pour C++ Référence de l'API
description: "Détermine où les ressources externes doivent être stockées. Écrivez System::String."
type: docs
weight: 92
url: /fr/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) méthode


Détermine où les ressources externes doivent être stockées. Écrivez [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
```

## Remarques


Exemple :
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