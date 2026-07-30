---
title: AddAutoShape()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova forma automatica con formattazione predefinita e la aggiunge alla fine della collezione di forme.
type: docs
weight: 313
url: /it/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) metodo

Crea una nuova forma automatica con formattazione predefinita e la aggiunge alla fine della collezione di forme.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Il [ShapeType](../../shapetype/) della forma automatica da aggiungere. |
| x | **float** | La coordinata x del riquadro della forma, in punti. |
| y | **float** | La coordinata y del riquadro della forma, in punti. |
| width | **float** | La larghezza del riquadro della forma, in punti. |
| height | **float** | L'altezza del riquadro della forma, in punti. |

### Valore restituito

Il [IAutoShape](../../iautoshape/) appena creato.

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) metodo

Crea una nuova forma automatica e la aggiunge alla fine della collezione di forme, opzionalmente inizializzandola con la formattazione predefinita del modello.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Il [ShapeType](../../shapetype/) della forma automatica da aggiungere. |
| x | **float** | La coordinata x del riquadro della forma, in punti. |
| y | **float** | La coordinata y del riquadro della forma, in punti. |
| width | **float** | La larghezza del riquadro della forma, in punti. |
| height | **float** | L'altezza del riquadro della forma, in punti. |
| createFromTemplate | **bool** | True per applicare lo stile predefinito del modello (stile semplice, testo centrato e nome non vuoto) alla nuova forma; false per creare la forma con tutte le proprietà impostate ai valori predefiniti. |

### Valore restituito

Il [IAutoShape](../../iautoshape/) appena creato.

## Vedi anche

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [IShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)