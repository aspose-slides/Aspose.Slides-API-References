---
title: Reorder()
second_title: Riferimento API di Aspose.Slides per C++
description: Sposta la forma specificata in una nuova posizione all'interno della collezione di forme.
type: docs
weight: 339
url: /it/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) metodo

Sposta la forma specificata in una nuova posizione all'interno della collezione di forme.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice di destinazione a base zero dove verrà collocata la forma. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Il [IShape](../../ishape/) da spostare all'interno della collezione. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) metodo

Sposta le forme specificate all'interno della collezione di forme, posizionandole a partire dall'indice fornito.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice di destinazione a base zero dove verrà collocata la prima forma specificata; le forme successive seguiranno nell'ordine fornito. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Una o più istanze di [IShape](../../ishape/) da spostare all'interno della collezione. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)