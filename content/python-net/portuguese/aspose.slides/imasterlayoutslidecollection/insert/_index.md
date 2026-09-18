---
title: insert method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Insere um novo slide de layout na posição especificada da coleção.

### Retorno

Slide inserido.



```python
def insert(self, index, layout_type, layout_name):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | Índice do novo slide. |
| layout_type | [`SlideLayoutType`](/slides/python-net/pt/aspose.slides/slidelayouttype) | Tipo de layout para um novo layout.<br/><br/>            Tipos de layout suportados: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Outros tipos de layout não são suportados no momento: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Nome para um novo layout. Se o nome fornecido já estiver em uso, será lançada uma ArgumentException.<br/><br/>            Se o parâmetro None for passado, o nome será gerado automaticamente com base no tipo de layout informado <br/><br/>            (por exemplo "Title Slide" ou "1_Title Slide", "2_..", etc.). |

### Observações

O layout inserido para o valor SlideLayoutType.Custom de `layout_type` contém nenhum marcador de posição e nenhuma forma.

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Lançada se for passado um valor não suportado para o parâmetro `layout_type`. Tipos de layout que não são suportados no momento: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada se o valor do nome do layout `layout_name` já estiver em uso nesta coleção de layouts. |



### Veja Também
* classe [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide)
* classe [`IMasterLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/imasterlayoutslidecollection)
* enumeração [`SlideLayoutType`](/slides/python-net/pt/aspose.slides/slidelayouttype)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)