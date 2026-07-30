---
title: Add()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una nuova diapositiva di layout alla fine della raccolta.
type: docs
weight: 27
url: /it/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) metodo

Aggiunge una nuova diapositiva di layout alla fine della raccolta.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Tipo di layout per un nuovo layout. Tipi di layout supportati: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Altri tipi di layout non sono attualmente supportati: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nome per un nuovo layout. Se il nome fornito è già in uso verrà sollevata l'ArgumentException. Se viene passato un parametro null, allora il nome viene generato automaticamente in base al tipo di layout fornito (per esempio \"Title Slide\" o \"1_Title Slide\", \"2_..\", ecc.). |

### Valore restituito

Diapositiva aggiunta.

## Osservazioni

1) Il layout aggiunto per il valore [SlideLayoutType::Custom](../../slidelayouttype/) di *layoutType* non contiene segnaposti né forme. 2) L'analogo di questo metodo è il metodo [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) accessibile tramite la proprietà [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Vedi anche

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [String](../../../system/string/)
* Classe [MasterLayoutSlideCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)