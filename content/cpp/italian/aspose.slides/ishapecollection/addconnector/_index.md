---
title: AddConnector()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova forma di connettore con lo stile predefinito del modello e la aggiunge alla fine della raccolta di forme.
type: docs
weight: 378
url: /it/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) metodo


Crea una nuova forma di connettore con lo stile predefinito del modello e la aggiunge alla fine della raccolta di forme.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Il [ShapeType](../../shapetype/) della forma di connettore da aggiungere. |
| x | **float** | La coordinata x del riquadro del connettore, in punti. |
| y | **float** | La coordinata y del riquadro del connettore, in punti. |
| width | **float** | La larghezza del riquadro del connettore, in punti. |
| height | **float** | L’altezza del riquadro del connettore, in punti. |

### Valore di ritorno

Il [IConnector](../../iconnector/) appena creato.

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) metodo


Crea una nuova forma di connettore e la aggiunge alla fine della raccolta di forme, applicando facoltativamente lo stile predefinito del modello.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Il [ShapeType](../../shapetype/) della forma di connettore da creare. |
| x | **float** | La coordinata x del riquadro del connettore, in punti. |
| y | **float** | La coordinata y del riquadro del connettore, in punti. |
| width | **float** | La larghezza del riquadro del connettore, in punti. |
| height | **float** | L’altezza del riquadro del connettore, in punti. |
| createFromTemplate | **bool** | True per applicare lo stile predefinito del modello (nome non vuoto, stile semplice); false per creare il connettore con i valori predefiniti delle proprietà. |

### Valore di ritorno

Il [IConnector](../../iconnector/) appena creato.

## Vedi anche

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IConnector](../../iconnector/)
* Classe [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)