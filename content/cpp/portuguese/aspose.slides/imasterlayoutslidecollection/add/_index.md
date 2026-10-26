---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona um novo slide de layout ao final da coleção.
type: docs
weight: 27
url: /pt/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) method

Adiciona um novo slide de layout ao final da coleção.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Tipo de layout para um novo layout. Tipos de layout suportados: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Outros tipos de layout não são suportados atualmente: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nome para um novo layout. Se o nome passado já estiver em uso, será lançada a ArgumentException. Se o parâmetro for null, o nome será gerado automaticamente em relação ao tipo de layout passado (por exemplo "Title Slide" ou "1_Title Slide", "2_..", etc.). |

### Valor de retorno

Slide adicionado.

## Observações

1) Layout adicionado para o valor [SlideLayoutType::Custom](../../slidelayouttype/) de *layoutType* não contém placeholders nem formas. 2) Análogo deste método é o método [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) acessado com a propriedade [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Veja Também

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [String](../../../system/string/)
* Classe [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)