---
title: AddClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme.
type: docs
weight: 547
url: /it/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method

Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | La forma da clonare. |
| x | **float** | La coordinata x del riquadro della nuova forma, in punti. |
| y | **float** | La coordinata y del riquadro della nuova forma, in punti. |
| width | **float** | La larghezza del riquadro della nuova forma, in punti. |
| height | **float** | L’altezza del riquadro della nuova forma, in punti. |

### Valore di ritorno

Il [IShape](../../ishape/) appena creato.

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) method

Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme. La nuova forma mantiene la larghezza e l’altezza della *sourceShape*.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | La forma da clonare. |
| x | **float** | La coordinata x del riquadro della nuova forma, in punti. |
| y | **float** | La coordinata y del riquadro della nuova forma, in punti. |

### Valore di ritorno

Il [IShape](../../ishape/) appena creato.

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) method

Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme. La forma clonata mantiene la posizione e le dimensioni originali.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
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
* Classe [ShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)