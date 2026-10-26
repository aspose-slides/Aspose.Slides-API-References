---
title: GetAllTextFrames()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert alle tekstkaders in een PPTX-presentatie.
type: docs
weight: 79
url: /nl/aspose.slides.util/slideutil/getalltextframes/
---
## SlideUtil::GetAllTextFrames(System::SharedPtr\<IPresentation\>, bool) methode

Retourneert alle tekstkaders in een PPTX-presentatie.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetAllTextFrames(System::SharedPtr<IPresentation> pres, bool withMasters)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Gescandeerde presentatie. |
| withMasters | **bool** | Bepaalt of master-slides gescand moeten worden. |

### Retourwaarde

Array van [TextFrame](../../../aspose.slides/textframe/) objecten.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrame](../../../aspose.slides/itextframe/)
* Class [IPresentation](../../../aspose.slides/ipresentation/)
* Class [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)