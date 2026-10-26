---
title: MarkdownImageSavingHandler
second_title: Référence de l'API Aspose.Slides for C++
description: Appelé pour chaque image non SVG (bitmap ou métafile) lors de l'exportation Markdown. Retourner true pour utiliser le lien spécifié, ou false pour appliquer la logique d'enregistrement par défaut.
type: docs
weight: 300
url: /fr/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef


Appelé pour chaque image non SVG (bitmap ou métafile) lors de l'exportation Markdown. 

 Renvoie **true** pour utiliser le *link* spécifié , 

 ou **false** pour appliquer la logique d'enregistrement par défaut.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```


## Voir aussi

* Classe [MarkdownSaveOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)