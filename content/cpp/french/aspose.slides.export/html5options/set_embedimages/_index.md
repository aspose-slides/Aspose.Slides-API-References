---
title: set_EmbedImages()
second_title: Aspose.Slides pour la référence API C++
description: Définit l'option d'intégration d'images. Écrire bool.
type: docs
weight: 66
url: /fr/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) méthode

Définit l'option d'insertion d'images. Écrire **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
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