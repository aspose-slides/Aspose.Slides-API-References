---
title: Insert()
second_title: Aspose.Slides per C++ Riferimento API
description: Inserisce una nuova diapositiva di layout nella posizione specificata della collezione.
type: docs
weight: 40
url: /it/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) metodo

Inserisce una nuova diapositiva di layout nella posizione specificata della collezione.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice della nuova diapositiva. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Tipo di layout per un nuovo layout. Tipi di layout supportati: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Altri tipi di layout non sono supportati al momento: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nome per un nuovo layout. Se il nome fornito è già in uso verrà sollevata l'eccezione ArgumentException. Se viene passato un parametro null, il nome viene generato automaticamente in base al tipo di layout fornito (ad esempio \"Title Slide\" o \"1_Title Slide\", \"2_..\", ecc.). |

### Valore di ritorno

Diapositiva inserita.

## Osservazioni

Layout inserito per il valore [SlideLayoutType::Custom](../../slidelayouttype/) di *layoutType* non contiene segnaposti né forme. 

## Vedi anche

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [String](../../../system/string/)
* Classe [MasterLayoutSlideCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)