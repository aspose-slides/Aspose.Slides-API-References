---
title: InsertClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato.
type: docs
weight: 560
url: /it/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) metodo

Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire la forma clonata. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Il [IShape](../../ishape/) da clonare. |
| x | **float** | La coordinata x del fotogramma della forma clonata, in punti. |
| y | **float** | La coordinata y del fotogramma della forma clonata, in punti. |
| width | **float** | La larghezza del fotogramma della forma clonata, in punti. |
| height | **float** | L'altezza del fotogramma della forma clonata, in punti. |

### Valore restituito

Il [IShape](../../ishape/) appena creato.

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) metodo

Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato. La nuova forma mantiene la larghezza e l'altezza della *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire la forma clonata. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Il [IShape](../../ishape/) da clonare. |
| x | **float** | La coordinata x del fotogramma della forma clonata, in punti. |
| y | **float** | La coordinata y del fotogramma della forma clonata, in punti. |

### Valore restituito

Il [IShape](../../ishape/) appena creato.

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) metodo

Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato. La forma clonata mantiene la posizione e le dimensioni originali.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale inserire la forma clonata. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Il [IShape](../../ishape/) da clonare. |

### Valore restituito

Il [IShape](../../ishape/) appena creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [ShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)