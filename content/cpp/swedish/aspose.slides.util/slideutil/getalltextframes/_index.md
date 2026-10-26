---
title: GetAllTextFrames()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar alla textramar i en PPTX-presentation.
type: docs
weight: 79
url: /sv/aspose.slides.util/slideutil/getalltextframes/
---
## SlideUtil::GetAllTextFrames(System::SharedPtr\<IPresentation\>, bool) metod


Returnerar alla textramar i en PPTX-presentation.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetAllTextFrames(System::SharedPtr<IPresentation> pres, bool withMasters)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Skannad presentation. |
| withMasters | **bool** | Bestämmer om masterbilder ska skannas. |

### Returvärde

Array av [TextFrame](../../../aspose.slides/textframe/)-objekt.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ITextFrame](../../../aspose.slides/itextframe/)
* Klass [IPresentation](../../../aspose.slides/ipresentation/)
* Klass [SlideUtil](../)
* Namnrymd [Aspose::Slides::Util](../../)
* Bibliotek [Aspose.Slides](../../../)