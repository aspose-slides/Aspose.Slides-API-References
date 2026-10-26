---
title: InsertAutoShape()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una nuova forma automatica e la inserisce nella collezione di forme all'indice specificato, applicando la formattazione predefinita del modello.
type: docs
weight: 339
url: /it/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) metodo


Crea una nuova forma automatica e la inserisce nella collezione di forme all'indice specificato, applicando la formattazione predefinita del modello.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
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

### Valore restituito

Il [IAutoShape](../../iautoshape/) appena creato.

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) metodo


Crea una nuova forma automatica e la inserisce nella collezione di forme all'indice specificato, opzionalmente inizializzandola con lo stile predefinito del modello.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
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
| createFromTemplate | **bool** | True per applicare lo stile predefinito del modello (inclusi nome non vuoto, stile semplice e testo centrato); false per creare la forma con tutte le proprietà impostate ai valori predefiniti. |

### Valore restituito

Il [IAutoShape](../../iautoshape/) appena creato.

## Vedi anche

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)