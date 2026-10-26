---
title: GetAllTextFrames()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt alle Textfelder in einer PPTX-Präsentation zurück.
type: docs
weight: 79
url: /de/aspose.slides.util/slideutil/getalltextframes/
---
## SlideUtil::GetAllTextFrames(System::SharedPtr\<IPresentation\>, bool) Methode

Gibt alle Textfelder in einer PPTX-Präsentation zurück.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetAllTextFrames(System::SharedPtr<IPresentation> pres, bool withMasters)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Durchsuchte Präsentation. |
| withMasters | **bool** | Bestimmt, ob Masterfolien durchsucht werden sollen. |

### Rückgabewert

Array von [TextFrame](../../../aspose.slides/textframe/)-Objekten.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ITextFrame](../../../aspose.slides/itextframe/)
* Klasse [IPresentation](../../../aspose.slides/ipresentation/)
* Klasse [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Bibliothek [Aspose.Slides](../../../)