---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona um novo slide de layout à apresentação.
type: docs
weight: 14
url: /pt/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) método

Adiciona um novo slide de layout à apresentação.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Slide mestre para um novo layout. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Tipo de layout para um novo layout. Tipos de layout suportados: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Outros tipos de layout não são suportados no momento: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nome para um novo layout. Se o nome fornecido já estiver em uso, será lançada a ArgumentException. Se o parâmetro for nulo, o nome será gerado automaticamente de acordo com o tipo de layout fornecido (por exemplo \"Title Slide\" ou \"1_Title Slide\", \"2_..\", etc.). |

### Valor de Retorno

Slide adicionado.

## Observações

1) Layout adicionado para o valor [SlideLayoutType::Custom](../../slidelayouttype/) de *layoutType* não contém placeholders nem formas. 2) Análogo deste método é o método [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) acessado pela propriedade [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/). 

## Ver Também

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Class [String](../../../system/string/)
* Class [IGlobalLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)