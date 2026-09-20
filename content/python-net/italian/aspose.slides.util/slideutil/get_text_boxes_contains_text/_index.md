---
title: get_text_boxes_contains_text method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.util/slideutil/get_text_boxes_contains_text/
weight: 70
---
## get_text_boxes_contains_text(slide, text, check_placeholder_text) {#ibaseslide-str-bool}
Restituisce tutti i riquadri di testo nella diapositiva specificata che contengono il testo fornito.

### Restituisce

Un array di oggetti [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe) che contengono il testo specificato.



```python
@staticmethod
def get_text_boxes_contains_text(slide, text, check_placeholder_text):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide) | La diapositiva da cercare. |
| text | **str** | Il testo da cercare nei riquadri di testo. |
| check_placeholder_text | **bool** | Indica se includere i riquadri di testo vuoti, ma il cui testo segnaposto contiene il testo cercato. |



### Vedi anche
* classe [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide)
* classe [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe)
* classe [`SlideUtil`](/slides/python-net/it/aspose.slides.util/slideutil)
* modulo [`aspose.slides.util`](/slides/python-net/it/aspose.slides.util)
* libreria [`Aspose.Slides`](/slides/python-net)