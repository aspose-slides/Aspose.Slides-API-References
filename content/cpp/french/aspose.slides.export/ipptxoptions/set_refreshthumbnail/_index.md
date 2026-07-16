---
title: set_RefreshThumbnail()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie si la vignette de la présentation sera rafraîchie. Écrire bool. Valeur par défaut : true.
type: docs
weight: 66
url: /fr/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) méthode

Spécifie si la vignette de la présentation sera rafraîchie. Écrire **bool**. La valeur par défaut est **true**.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## Remarques

Lorsque la valeur de l'option est **true**, la nouvelle vignette sera générée.

Lorsque la valeur de l'option est **false**, la vignette actuelle sera enregistrée telle quelle.

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