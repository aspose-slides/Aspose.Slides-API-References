---
title: GetSlideComments()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert alle dia-opmerkingen die door een specifieke auteur zijn toegevoegd.
type: docs
weight: 209
url: /nl/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) method

Retourneert alle dia-opmerkingen die door een specifieke auteur zijn toegevoegd.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Auteur van de te vinden opmerkingen of null om alle opmerkingen te retourneren. |

### Retourwaarde

Array van [Comment](../../comment/).

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IComment](../../icomment/)
* Klasse [ICommentAuthor](../../icommentauthor/)
* Klasse [Slide](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)