---
title: AddAutoShape()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una nuova forma automatica con formattazione predefinita e la aggiunge alla fine della raccolta di forme.
type: docs
weight: 352
url: /it/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) metodo

Crea una nuova forma automatica con formattazione predefinita e la aggiunge alla fine della raccolta di forme.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Il [ShapeType](../../shapetype/) della forma automatica da aggiungere. |
| x | **float** | La coordinata x del frame di shape\u2019s, in punti. |
| y | **float** | La coordinata y del frame di shape\u2019s, in punti. |
| width | **float** | La larghezza del frame di shape\u2019s, in punti. |
| height | **float** | L'altezza del frame di shape\u2019s, in punti. |

### Valore di ritorno

Il [IAutoShape](../../iautoshape/) appena creato.

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) metodo

Crea una nuova forma automatica e la aggiunge alla fine della raccolta di forme, opzionalmente inizializzandola con la formattazione predefinita del modello.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Il [ShapeType](../../shapetype/) della forma automatica da aggiungere. |
| x | **float** | La coordinata x del frame di shape\u2019s, in punti. |
| y | **float** | La coordinata y del frame di shape\u2019s, in punti. |
| width | **float** | La larghezza del frame di shape\u2019s, in punti. |
| height | **float** | L'altezza del frame di shape\u2019s, in punti. |
| createFromTemplate | **bool** | True per applicare lo stile predefinito del modello (stile semplice, testo centrato e nome non vuoto) alla nuova forma; false per creare la forma con tutte le proprietà impostate ai loro valori predefiniti. |

### Valore di ritorno

Il [IAutoShape](../../iautoshape/) appena creato.

## Vedi anche

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)