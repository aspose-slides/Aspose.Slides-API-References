---
title: InsertConnector()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova forma connettore e la inserisce nella collezione di forme all'indice specificato, applicando lo stile predefinito del modello.
type: docs
weight: 430
url: /it/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) method

Crea una nuova forma connettore e la inserisce nella collezione di forme all'indice specificato, applicando lo stile predefinito del modello.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice a base zero al quale inserire la forma connettore. |
| shapeType | [ShapeType](../../shapetype/) | Il [ShapeType](../../shapetype/) della forma connettore da inserire. |
| x | **float** | La coordinata x del frame del connettore, in punti. |
| y | **float** | La coordinata y del frame del connettore, in punti. |
| width | **float** | La larghezza del frame del connettore, in punti. |
| height | **float** | L'altezza del frame del connettore, in punti. |

### Valore restituito

Il [IConnector](../../iconnector/) appena creato.

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) method

Crea una nuova forma connettore e la inserisce nella collezione di forme all'indice specificato, opzionalmente applicando lo stile predefinito del modello.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice a base zero al quale inserire la forma connettore. |
| shapeType | [ShapeType](../../shapetype/) | Il [ShapeType](../../shapetype/) della forma connettore da inserire. |
| x | **float** | La coordinata x del frame del connettore, in punti. |
| y | **float** | La coordinata y del frame del connettore, in punti. |
| width | **float** | La larghezza del frame del connettore, in punti. |
| height | **float** | L'altezza del frame del connettore, in punti. |
| createFromTemplate | **bool** | True per applicare lo stile predefinito del modello (nome non vuoto, stile semplice); false per creare il connettore con i valori predefiniti delle proprietà. |

### Valore restituito

Il [IConnector](../../iconnector/) appena creato.

## Vedi anche

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IConnector](../../iconnector/)
* Classe [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)