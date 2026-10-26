---
title: get_RefreshThumbnail()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie si la miniature de la présentation sera rafraîchie. Lecture bool. Valeur par défaut est true.
type: docs
weight: 53
url: /fr/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() méthode

Spécifie si la miniature de la présentation sera rafraîchie. Lecture **bool**. La valeur par défaut est **true**.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
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

* Classe [IPptxOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)