---
title: InsertClone()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una copia della forma specificata e la inserisce nella collezione di forme all'indice specificato.
type: docs
weight: 508
url: /it/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) metodo


Crea una copia della forma specificata e la inserisce nella collezione di forme all'indice specificato.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire la forma clonata. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Il [IShape](../../ishape/) da clonare. |
| x | **float** | La coordinata x del riquadro della forma clonata, in punti. |
| y | **float** | La coordinata y del riquadro della forma clonata, in punti. |
| width | **float** | La larghezza del riquadro della forma clonata, in punti. |
| height | **float** | L'altezza del riquadro della forma clonata, in punti. |

### Valore di ritorno

Il [IShape](../../ishape/) appena creato.

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) metodo


Crea una copia della forma specificata e la inserisce nella collezione di forme all'indice specificato. La nuova forma mantiene la larghezza e l’altezza della *sourceShape*.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire la forma clonata. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Il [IShape](../../ishape/) da clonare. |
| x | **float** | La coordinata x del riquadro della forma clonata, in punti. |
| y | **float** | La coordinata y del riquadro della forma clonata, in punti. |

### Valore di ritorno

Il [IShape](../../ishape/) appena creato.

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) metodo


Crea una copia della forma specificata e la inserisce nella collezione di forme all'indice specificato. La forma clonata mantiene la posizione e le dimensioni dell'originale.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire la forma clonata. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Il [IShape](../../ishape/) da clonare. |

### Valore di ritorno

Il [IShape](../../ishape/) appena creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [IShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)