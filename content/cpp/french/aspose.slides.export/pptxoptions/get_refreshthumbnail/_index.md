---
title: get_RefreshThumbnail()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie si la miniature de la présentation sera rafraîchie. Lecture bool. Valeur par défaut : true.
type: docs
weight: 53
url: /fr/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() méthode


Spécifie si la miniature de la présentation sera rafraîchie. Lecture **bool**. La valeur par défaut est **true**.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## Remarques


Lorsque la valeur de l'option est **true**, la nouvelle miniature sera générée.

Lorsque la valeur de l'option est **false**, la miniature actuelle sera enregistrée telle quelle.

Exemple : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Voir aussi

* Classe [PptxOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)