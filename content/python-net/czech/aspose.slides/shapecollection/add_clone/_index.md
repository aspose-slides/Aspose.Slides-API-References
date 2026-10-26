---
title: add_clone method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/shapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů.
            Klonovaný tvar zachovává původní polohu a velikost.

### Vrací

Nově vytvořený [`IShape`](/slides/python-net/cs/aspose.slides/ishape).

```python
def add_clone(self, source_shape):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/cs/aspose.slides/ishape) | [`IShape`](/slides/python-net/cs/aspose.slides/ishape) k klonování. |

## add_clone(self, source_shape, x, y) {#ishape-float-float}
Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů.
            Nový tvar si zachovává šířku a výšku `source_shape`.

### Vrací

Nově vytvořený [`IShape`](/slides/python-net/cs/aspose.slides/ishape).

```python
def add_clone(self, source_shape, x, y):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/cs/aspose.slides/ishape) | Tvar k klonování. |
| x | **float** | Souřadnice x rámce nového tvaru, v bodech. |
| y | **float** | Souřadnice y rámce nového tvaru, v bodech. |

## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů.

### Vrací

Nově vytvořený [`IShape`](/slides/python-net/cs/aspose.slides/ishape).

```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/cs/aspose.slides/ishape) | Tvar k klonování. |
| x | **float** | Souřadnice x rámce nového tvaru, v bodech. |
| y | **float** | Souřadnice y rámce nového tvaru, v bodech. |
| width | **float** | Šířka rámce nového tvaru, v bodech. |
| height | **float** | Výška rámce nového tvaru, v bodech. |

### Viz také
* třída [`IShape`](/slides/python-net/cs/aspose.slides/ishape)
* třída [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)