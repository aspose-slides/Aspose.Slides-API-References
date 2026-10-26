---
title: AddClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme.
type: docs
weight: 495
url: /it/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) metodo


Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | La forma da clonare. |
| x | **float** | La coordinata x del riquadro della forma clonata, in punti. |
| y | **float** | La coordinata y del riquadro della forma clonata, in punti. |
| width | **float** | La larghezza del riquadro della forma clonata, in punti. |
| height | **float** | L’altezza del riquadro della forma clonata, in punti. |

### Valore di ritorno

Il [IShape](../../ishape/) appena creato.

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) metodo


Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme. La nuova forma mantiene la larghezza e l’altezza della *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Il [IShape](../../ishape/) da clonare. |
| x | **float** | La coordinata x del riquadro della forma clonata, in punti. |
| y | **float** | La coordinata y del riquadro della forma clonata, in punti. |

### Valore di ritorno

Il [IShape](../../ishape/) appena creato.

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) metodo


Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme. La forma clonata mantiene la posizione e le dimensioni originali.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Il [IShape](../../ishape/) da clonare. |

### Valore di ritorno

Il [IShape](../../ishape/) appena creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [IShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)