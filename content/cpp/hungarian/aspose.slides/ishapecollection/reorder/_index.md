---
title: Reorder()
second_title: Aspose.Slides C++ API referencia
description: Áthelyezi a megadott alakzatot a alakzatgyűjteményen belül egy új pozícióba.
type: docs
weight: 300
url: /hu/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) metódus


Áthelyezi a megadott alakzatot a alakzatgyűjteményen belül egy új pozícióba.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nullától induló célindex, ahol az alakzat el lesz helyezve. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A [IShape](../../ishape/) a gyűjteményen belül áthelyezendő. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) metódus


Áthelyezi a megadott alakzatokat a alakzatgyűjteményben, a megadott indexnél kezdve elhelyezve őket.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nullától induló célindex, ahol az első megadott alakzat lesz elhelyezve; a további alakzatok a megadott sorrendben követik. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Egy vagy több [IShape](../../ishape/) példány a gyűjteményen belül áthelyezendő. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)