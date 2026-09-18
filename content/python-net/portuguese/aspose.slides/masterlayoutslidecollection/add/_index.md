---
title: add method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Adiciona um novo slide de layout ao final da coleção.

### Retorna

Slide adicionado.

```python
def add(self, layout_type, layout_name):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/pt/aspose.slides/slidelayouttype) | Tipo de layout para um novo layout.<br/><br/>            Tipos de layout suportados: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Outros tipos de layout não são suportados no momento: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nome para um novo layout. Se o nome passado já estiver em uso, será lançada uma ArgumentException.<br/><br/>            Se o parâmetro None for passado, então o nome será gerado automaticamente em relação ao tipo de layout passado <br/><br/>            (for example "Title Slide" or "1_Title Slide", "2_..", etc.). |

### Observações

1) Layout adicionado para o valor SlideLayoutType.Custom de `layout_type` não contém espaços reservados nem formas.  
2) Análogo deste método é o método **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** acessado com [`IPresentation.layout_slides`](/slides/python-net/pt/aspose.slides/ipresentation/layout_slides) property.

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Lançada se um valor não suportado do parâmetro `layout_type` for passado. Tipos de layout que não são suportados no momento: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada se o valor do nome do layout `layout_name` já estiver em uso nesta coleção de layouts. |

### Veja Também
* classe [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide)
* classe [`MasterLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection)
* enumeração [`SlideLayoutType`](/slides/python-net/pt/aspose.slides/slidelayouttype)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)