---
title: GetSlideComments()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt alle Folienkommentare zurück, die von einem bestimmten Autor hinzugefügt wurden.
type: docs
weight: 209
url: /de/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) Methode

Gibt alle Folienkommentare zurück, die von einem bestimmten Autor hinzugefügt wurden.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Autor der zu findenden Kommentare oder null, um alle Kommentare zurückzugeben. |

### Rückgabewert

Array von [Comment](../../comment/).

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IComment](../../icomment/)
* Klasse [ICommentAuthor](../../icommentauthor/)
* Klasse [Slide](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)