---
title: add_group_shape method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ishapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Crea una nuova forma di gruppo vuota e la aggiunge alla fine della raccolta di forme.
Il riquadro del gruppo si aggiusterà automaticamente per contenere tutte le forme aggiunte.

### Restituisce

La nuova [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape).

```python
def add_group_shape(self):
    ...
```

## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Crea una nuova forma di gruppo, converte l'immagine SVG specificata in forme individuali e aggiunge il gruppo risultante alla fine della raccolta di forme.

### Restituisce

La nuova [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape).

```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/it/aspose.slides/isvgimage) | Il [`ISvgImage`](/slides/python-net/it/aspose.slides/isvgimage) contenente il contenuto vettoriale da convertire in forme. |
| x | **float** | La coordinata x del riquadro del gruppo, in punti. |
| y | **float** | La coordinata y del riquadro del gruppo, in punti. |
| width | **float** | La larghezza del riquadro del gruppo, in punti. |
| height | **float** | L'altezza del riquadro del gruppo, in punti. |

### Vedi anche
* classe [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape)
* classe [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection)
* classe [`ISvgImage`](/slides/python-net/it/aspose.slides/isvgimage)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)