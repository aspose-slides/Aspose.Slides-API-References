---
title: add method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Adiciona um novo slide de layout à apresentação.

### Retorna

Slide adicionado.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/pt/aspose.slides/imasterslide) | Slide mestre para um novo layout. |
| layout_type | [`SlideLayoutType`](/slides/python-net/pt/aspose.slides/slidelayouttype) | Tipo de layout para um novo layout.<br/><br/>Tipos de layout suportados: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>Outros tipos de layout não são suportados atualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nome para um novo layout. Se o nome passado já estiver em uso, será lançada a ArgumentException.<br/><br/>Se o parâmetro None for passado, então o nome será gerado automaticamente de acordo com o tipo de layout passado (por exemplo "Title Slide" ou "1_Title Slide", "2_..", etc.). |

### Observações

1) O layout adicionado para o valor SlideLayoutType.Custom de `layout_type` não contém marcadores de posição nem formas.  
2) Análogo deste método é o método **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** acessado com a propriedade [`IMasterSlide.layout_slides`](/slides/python-net/pt/aspose.slides/imasterslide/layout_slides).

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Lançada se for passado um valor não suportado para o parâmetro `layout_type`. Tipos de layout que não são suportados atualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lançada se `master` for None. |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada se `master` pertencer a outra apresentação. |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada se o valor do nome do layout `layout_name` já estiver em uso na coleção de layouts de `master`. |



### Veja Também
* classe [`GlobalLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/globallayoutslidecollection)
* classe [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/pt/aspose.slides/imasterslide)
* enumeração [`SlideLayoutType`](/slides/python-net/pt/aspose.slides/slidelayouttype)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)