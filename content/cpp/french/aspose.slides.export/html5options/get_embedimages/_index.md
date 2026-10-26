---
title: get_EmbedImages()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie l'option d'intégration d'images. Lecture bool.
type: docs
weight: 53
url: /fr/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() méthode


Renvoie l'option d'intégration d'images. Lecture **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
```

## Remarques


Exemple:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Voir aussi

* Classe [Html5Options](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)