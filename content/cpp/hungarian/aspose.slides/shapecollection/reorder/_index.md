---
title: Reorder()
second_title: Aspose.Slides C++ API Referencia
description: Áthelyezi a megadott alakzatot a forma gyűjteményen belül egy új pozícióba.
type: docs
weight: 339
url: /hu/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) metódus


Áthelyezi a megadott alakzatot a forma gyűjteményen belül egy új pozícióba.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nulla alapján indexelt célindex, ahová az alakzat helyeződik. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A [IShape](../../ishape/) a gyűjteményen belül áthelyezendő. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) metódus


Áthelyezi a megadott alakzatokat a forma gyűjteményen belül, és a megadott indexnél kezdi elhelyezésüket.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nulla alapján indexelt célindex, ahová az első megadott alakzat helyeződik; a további alakzatok az adott sorrendben követik. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Egy vagy több [IShape](../../ishape/) példány, amelyeket a gyűjteményen belül át kell helyezni. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)