---
title: Insert()
second_title: Referência da API Aspose.Slides para C++
description: Insere um novo slide de layout na posição especificada da coleção.
type: docs
weight: 40
url: /pt/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) method

Insere um novo slide de layout na posição especificada da coleção.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice do novo slide. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Tipo de layout para um novo layout. Tipos de layout suportados: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Outros tipos de layout não são suportados atualmente: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Nome para um novo layout. Se o nome passado já estiver em uso, ArgumentException será lançada. Se for passado um parâmetro nulo, o nome será gerado automaticamente de acordo com o tipo de layout passado (por exemplo \"Title Slide\" ou \"1_Title Slide\", \"2_..\", etc.). |

### Valor de Retorno

Slide inserido.

## Observações

Layout inserido para o valor [SlideLayoutType::Custom](../../slidelayouttype/) de *layoutType* não contém espaços reservados nem formas. 

## Veja Também

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [String](../../../system/string/)
* Classe [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)