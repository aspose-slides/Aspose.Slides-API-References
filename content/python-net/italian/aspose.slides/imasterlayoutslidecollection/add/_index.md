---
title: add method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/imasterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Aggiunge una nuova diapositiva di layout alla fine della collezione.

### Restituisce

Diapositiva aggiunta.



```python
def add(self, layout_type, layout_name):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/it/aspose.slides/slidelayouttype) | Tipo di layout per un nuovo layout.<br/><br/>Tipi di layout supportati: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>Altri tipi di layout non sono attualmente supportati: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nome per un nuovo layout. Se il nome fornito è già in uso verrà sollevata l'ArgumentException.<br/><br/>Se viene passato il parametro None, il nome viene generato automaticamente in base al tipo di layout fornito <br/><br/> (per esempio "Title Slide" o "1_Title Slide", "2_..", ecc.). |

### Osservazioni

1) Il layout aggiunto per il valore SlideLayoutType.Custom di `layout_type` non contiene segnaposto né forme.
2) L'analogo di questo metodo è il metodo **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** a cui si accede tramite la proprietà [`IPresentation.layout_slides`](/slides/python-net/it/aspose.slides/ipresentation/layout_slides).

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Sollevata se viene passato un valore non supportato per il parametro `layout_type`. Tipi di layout non supportati attualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Sollevata se il valore del nome del layout `layout_name` è già in uso in questa collezione di layout. |



### Vedi anche
* classe [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide)
* classe [`IMasterLayoutSlideCollection`](/slides/python-net/it/aspose.slides/imasterlayoutslidecollection)
* enumerazione [`SlideLayoutType`](/slides/python-net/it/aspose.slides/slidelayouttype)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)