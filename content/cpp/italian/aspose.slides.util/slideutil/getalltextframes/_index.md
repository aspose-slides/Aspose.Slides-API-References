---
title: GetAllTextFrames()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce tutti i riquadri di testo in una presentazione PPTX.
type: docs
weight: 79
url: /it/aspose.slides.util/slideutil/getalltextframes/
---
## SlideUtil::GetAllTextFrames(System::SharedPtr\<IPresentation\>, bool) metodo

Restituisce tutti i riquadri di testo in una presentazione PPTX.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetAllTextFrames(System::SharedPtr<IPresentation> pres, bool withMasters)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Presentazione scansionata. |
| withMasters | **bool** | Determina se le diapositive master devono essere scansionate. |

### Return Value

Array di oggetti [TextFrame](../../../aspose.slides/textframe/).

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITextFrame](../../../aspose.slides/itextframe/)
* Classe [IPresentation](../../../aspose.slides/ipresentation/)
* Classe [SlideUtil](../)
* Spazio dei nomi [Aspose::Slides::Util](../../)
* Libreria [Aspose.Slides](../../../)