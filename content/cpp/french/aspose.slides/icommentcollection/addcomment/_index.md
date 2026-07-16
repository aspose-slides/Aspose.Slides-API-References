---
title: AddComment()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute un nouveau commentaire à la fin d'une collection.
type: docs
weight: 14
url: /fr/aspose.slides/icommentcollection/addcomment/
---
## ICommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) méthode

Ajoute un nouveau commentaire à la fin d'une collection.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texte brut du nouveau commentaire. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) dans une présentation où ajouter un nouveau commentaire. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Position sur une diapositive où ajouter un nouveau commentaire. |
| creationTime | [System::DateTime](../../../system/datetime/) | Heure de création du commentaire. |

### Valeur de retour

Commentaire ajouté.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComment](../../icomment/)
* Classe [String](../../../system/string/)
* Classe [ISlide](../../islide/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [DateTime](../../../system/datetime/)
* Classe [ICommentCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)