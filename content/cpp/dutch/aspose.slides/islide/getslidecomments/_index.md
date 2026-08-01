---
title: GetSlideComments()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert alle dia-opmerkingen die door een specifieke auteur zijn toegevoegd.
type: docs
weight: 118
url: /nl/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) methode


Retourneert alle diaopmerkingen die door een specifieke auteur zijn toegevoegd.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Auteur van de op te zoeken opmerkingen of null om alle opmerkingen te retourneren. |

### Retourwaarde

Array van [IComment](../../icomment/).

## Zie Ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IComment](../../icomment/)
* Klasse [ICommentAuthor](../../icommentauthor/)
* Klasse [ISlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)