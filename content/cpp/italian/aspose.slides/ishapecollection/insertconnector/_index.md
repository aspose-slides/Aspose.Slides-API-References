---
title: InsertConnector()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova forma connettore e la inserisce nella raccolta di forme all'indice specificato, applicando lo stile predefinito del modello.
type: docs
weight: 391
url: /it/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) metodo

Crea una nuova forma connettore e la inserisce nella raccolta di forme all'indice specificato, applicando lo stile predefinito del modello.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'indice a base zero al quale inserire la forma connettore. |
| shapeType | [ShapeType](../../shapetype/) | Il [ShapeType](../../shapetype/) della forma connettore da inserire. |
| x | **float** | La coordinata x del riquadro del connettore, in punti. |
| y | **float** | La coordinata y del riquadro del connettore, in punti. |
| width | **float** | La larghezza del riquadro del connettore, in punti. |
| height | **float** | L'altezza del riquadro del connettore, in punti. |

### Valore di ritorno

Il nuovo [IConnector](../../iconnector/).

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) metodo

Crea una nuova forma connettore e la inserisce nella raccolta di forme all'indice specificato, applicando opzionalmente lo stile predefinito del modello.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'indice a base zero al quale inserire la forma connettore. |
| shapeType | [ShapeType](../../shapetype/) | Il [ShapeType](../../shapetype/) della forma connettore da inserire. |
| x | **float** | La coordinata x del riquadro del connettore, in punti. |
| y | **float** | La coordinata y del riquadro del connettore, in punti. |
| width | **float** | La larghezza del riquadro del connettore, in punti. |
| height | **float** | L'altezza del riquadro del connettore, in punti. |
| createFromTemplate | **bool** | True per applicare lo stile predefinito del modello (nome non vuoto, stile semplice); false per creare il connettore con i valori predefiniti delle proprietà. |

### Valore di ritorno

Il nuovo [IConnector](../../iconnector/).

## Vedi anche

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IConnector](../../iconnector/)
* Classe [IShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)