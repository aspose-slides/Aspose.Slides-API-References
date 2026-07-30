---
title: Add()
second_title: Aspose.Slides per C++ Riferimento API
description: Aggiunge una nuova diapositiva di layout alla fine della collezione.
type: docs
weight: 27
url: /it/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) method

Aggiunge una nuova diapositiva di layout alla fine della collezione.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Tipo di layout per un nuovo layout. I tipi di layout supportati: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Altri tipi di layout non sono attualmente supportati: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nome per un nuovo layout. Se il nome fornito è già in uso verrà sollevata l'ArgumentException. Se viene passato un parametro null, allora il nome verrà generato automaticamente in base al tipo di layout fornito (ad esempio "Title Slide" o "1_Title Slide", "2_..", ecc.). |

### Valore restituito

Diapositiva aggiunta.

## Osservazioni

1) Il layout aggiunto per il valore [SlideLayoutType::Custom](../../slidelayouttype/) di *layoutType* non contiene segnaposti né forme. 2) L'analogo di questo metodo è il metodo [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) accessibile tramite la proprietà [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Vedi anche

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [String](../../../system/string/)
* Classe [IMasterLayoutSlideCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)