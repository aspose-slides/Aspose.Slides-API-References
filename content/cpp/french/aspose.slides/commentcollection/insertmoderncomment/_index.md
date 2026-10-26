---
title: InsertModernComment()
second_title: Référence de l'API Aspose.Slides pour C++
description: Insérer un nouveau commentaire moderne dans une collection à l'index spécifié.
type: docs
weight: 92
url: /fr/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) méthode

Insérer un nouveau commentaire moderne dans une collection à l'index spécifié.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indice de l'élément dans une collection où le commentaire moderne doit être inséré. |
| text | [System::String](../../../system/string/) | Texte brut d'un nouveau commentaire moderne. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) dans une présentation où ajouter un nouveau commentaire moderne. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) sur une diapositive à laquelle un nouveau commentaire moderne est associé. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position sur une diapositive où ajouter un nouveau commentaire moderne. |
| creationTime | [System::DateTime](../../../system/datetime/) | Moment de création d'un commentaire moderne. |

### Valeur de retour

Commentaire moderne inséré.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IModernComment](../../imoderncomment/)
* Classe [String](../../../system/string/)
* Classe [ISlide](../../islide/)
* Classe [IShape](../../ishape/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [DateTime](../../../system/datetime/)
* Classe [CommentCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)