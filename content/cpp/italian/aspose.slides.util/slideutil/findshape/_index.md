---
title: FindShape()
second_title: Riferimento API di Aspose.Slides per C++
description: Trova la forma tramite il testo alternativo in una presentazione PPTX.
type: docs
weight: 1
url: /it/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) method

Trova la forma tramite il testo alternativo in una presentazione PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Presentazione scansionata. |
| altText | [System::String](../../../system/string/) | Testo alternativo di una forma. |

### Valore di ritorno

[Shape](../../../aspose.slides/shape/) o null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) method

Trova la forma tramite il testo alternativo su una diapositiva in una presentazione PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Diapositiva scansionata. |
| altText | [System::String](../../../system/string/) | Testo alternativo di una forma. |

### Valore di ritorno

[Shape](../../../aspose.slides/shape/) o null.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../../aspose.slides/ishape/)
* Classe [IPresentation](../../../aspose.slides/ipresentation/)
* Classe [String](../../../system/string/)
* Classe [SlideUtil](../)
* Classe [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Spazio dei nomi [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)