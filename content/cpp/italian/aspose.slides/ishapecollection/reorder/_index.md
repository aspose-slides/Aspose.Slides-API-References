---
title: Reorder()
second_title: Riferimento API di Aspose.Slides per C++
description: Sposta la forma specificata in una nuova posizione all'interno della raccolta di forme.
type: docs
weight: 300
url: /it/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) metodo


Sposta la forma specificata in una nuova posizione all'interno della raccolta di forme.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice di destinazione basato su zero dove verrà posizionata la forma. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Il [IShape](../../ishape/) da spostare all'interno della raccolta. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) metodo


Sposta le forme specificate all'interno della raccolta di forme, posizionandole a partire dall'indice fornito.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice di destinazione basato su zero dove verrà posizionata la prima forma specificata; le forme successive seguono nell'ordine fornito. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Una o più istanze di [IShape](../../ishape/) da spostare all'interno della raccolta. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IShape](../../ishape/)
* Classe [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)