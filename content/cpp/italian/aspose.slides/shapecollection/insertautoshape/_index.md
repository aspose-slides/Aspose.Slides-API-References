---
title: InsertAutoShape()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova forma automatica e la inserisce nella collezione di forme all'indice specificato, applicando la formattazione predefinita del modello.
type: docs
weight: 378
url: /it/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) metodo

Crea una nuova forma automatica e la inserisce nella collezione di forme all'indice specificato, applicando la formattazione predefinita del modello.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire la nuova forma automatica. |
| shapeType | [ShapeType](../../shapetype/) | Il [ShapeType](../../shapetype/) della forma automatica da inserire. |
| x | **float** | La coordinata x del riquadro della forma, in punti. |
| y | **float** | La coordinata y del riquadro della forma, in punti. |
| width | **float** | La larghezza del riquadro della forma, in punti. |
| height | **float** | L'altezza del riquadro della forma, in punti. |

### Valore di ritorno

Il [IAutoShape](../../iautoshape/) appena creato.

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) metodo

Crea una nuova forma automatica e la inserisce nella collezione di forme all'indice specificato, opzionalmente inizializzandola con lo stile predefinito del modello.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire la forma automatica. |
| shapeType | [ShapeType](../../shapetype/) | Il [ShapeType](../../shapetype/) della forma automatica da inserire. |
| x | **float** | La coordinata x del riquadro della forma, in punti. |
| y | **float** | La coordinata y del riquadro della forma, in punti. |
| width | **float** | La larghezza del riquadro della forma, in punti. |
| height | **float** | L'altezza del riquadro della forma, in punti. |
| createFromTemplate | **bool** | True per applicare lo stile predefinito del modello (incluso un nome non vuoto, stile semplice e testo centrato); false per creare la forma con tutte le proprietà impostate ai valori predefiniti. |

### Valore di ritorno

Il [IAutoShape](../../iautoshape/) appena creato.

## Vedi anche

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)