---
title: GetTextBoxesContainsText()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce tutti i riquadri di testo nella diapositiva specificata che contengono il testo fornito.
type: docs
weight: 66
url: /it/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) metodo


Restituisce tutti i riquadri di testo nella diapositiva specificata che contengono il testo fornito.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | La diapositiva da cercare. |
| text | [System::String](../../../system/string/) | Il testo da cercare nei riquadri di testo. |
| checkPlaceholderText | **bool** | Indica se includere i riquadri di testo vuoti, ma il cui testo segnaposto contiene il testo di ricerca. |

### Valore di ritorno

Un array di oggetti [ITextFrame](../../../aspose.slides/itextframe/) che contengono il testo specificato.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrame](../../../aspose.slides/itextframe/)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Class [String](../../../system/string/)
* Class [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)