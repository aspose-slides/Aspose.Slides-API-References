---
title: add method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Aggiunge una nuova diapositiva di layout alla presentazione.

### Restituisce

Diapositiva aggiunta.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/it/aspose.slides/imasterslide) | Diapositiva master per un nuovo layout. |
| layout_type | [`SlideLayoutType`](/slides/python-net/it/aspose.slides/slidelayouttype) | Tipo di layout per un nuovo layout.<br/><br/>            Tipi di layout supportati: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Altri tipi di layout non sono supportati al momento: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nome per un nuovo layout. Se il nome fornito è già in uso verrà sollevata ArgumentException.<br/><br/>            Se viene passato il parametro None, il nome viene generato automaticamente in base al tipo di layout fornito <br/><br/>            (ad esempio "Title Slide" o "1_Title Slide", "2_..", ecc.). |

### Osservazioni

1) Il layout aggiunto per il valore SlideLayoutType.Custom di `layout_type` 
            non contiene segnaposti né forme.
2) L'equivalente di questo metodo è il metodo **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste**
            a cui si accede tramite la proprietà [`IMasterSlide.layout_slides`](/slides/python-net/it/aspose.slides/imasterslide/layout_slides) property.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Generata se viene passato un valore non supportato per il parametro `layout_type`. Tipi di layout non supportati al momento: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Generata se `master` è None. |
| **RuntimeError(Proxy error(ArgumentException))** | Generata se `master` appartiene a un'altra presentazione. |
| **RuntimeError(Proxy error(ArgumentException))** | Generata se il valore del nome del layout `layout_name` è già in uso nella collezione dei layout di `master`. |



### Vedi anche
* classe [`IGlobalLayoutSlideCollection`](/slides/python-net/it/aspose.slides/igloballayoutslidecollection)
* classe [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/it/aspose.slides/imasterslide)
* enumerazione [`SlideLayoutType`](/slides/python-net/it/aspose.slides/slidelayouttype)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)