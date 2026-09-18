---
title: reorder method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/ishapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
Move a forma especificada para uma nova posição dentro da coleção de formas.

```python
def reorder(self, index, shape):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice de destino baseado em zero onde a forma será colocada. |
| shape | [`IShape`](/slides/python-net/pt/aspose.slides/ishape) | O [`IShape`](/slides/python-net/pt/aspose.slides/ishape) a ser movido dentro da coleção. |

## reorder(self, index, shapes) {#int-listishape}
Move as formas especificadas dentro da coleção de formas, posicionando-as a partir do índice fornecido.

```python
def reorder(self, index, shapes):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice de destino baseado em zero onde a primeira forma especificada será colocada; <br/><br/>            formas subsequentes seguem na ordem fornecida. |
| shapes | **List[IShape]** | Uma ou mais instâncias de [`IShape`](/slides/python-net/pt/aspose.slides/ishape) para mover dentro da coleção. |

### Veja também
* classe [`IShape`](/slides/python-net/pt/aspose.slides/ishape)
* classe [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)