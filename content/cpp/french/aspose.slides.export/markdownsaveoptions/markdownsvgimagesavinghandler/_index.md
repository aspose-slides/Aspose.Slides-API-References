---
title: MarkdownSvgImageSavingHandler
second_title: Référence API Aspose.Slides pour C++
description: Appelé pour chaque image SVG lors de l'exportation Markdown. Retourne true pour utiliser le lien spécifié, ou false pour appliquer la logique d'enregistrement par défaut.
type: docs
weight: 313
url: /fr/aspose.slides.export/markdownsaveoptions/markdownsvgimagesavinghandler/
---
## MarkdownSvgImageSavingHandler typedef


Appelé pour chaque image SVG lors de l'exportation Markdown. 

 Renvoie **true** pour utiliser le *lien* , 

 ou **false** pour appliquer la logique d'enregistrement par défaut.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownSvgImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<ISvgImage>, System::String&)>
```


## Voir aussi

* Classe [MarkdownSaveOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)