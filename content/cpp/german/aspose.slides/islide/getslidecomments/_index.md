---
title: GetSlideComments()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt alle Folienkommentare zurück, die von einem bestimmten Autor hinzugefügt wurden.
type: docs
weight: 118
url: /de/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) Methode

Gibt alle Folienkommentare zurück, die von einem bestimmten Autor hinzugefügt wurden.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```

### Parameter

| Parameter | Type | Description |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Autor der zu findenden Kommentare oder null, um alle Kommentare zurückzugeben. |

### Rückgabewert

Array von [IComment](../../icomment/).

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IComment](../../icomment/)
* Klasse [ICommentAuthor](../../icommentauthor/)
* Klasse [ISlide](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)