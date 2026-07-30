---
title: Reorder()
second_title: Aspose.Slides pro C++ API referenci
description: Přesune zadaný tvar do nového umístění v kolekci tvarů.
type: docs
weight: 339
url: /cs/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) metoda

Přesune zadaný tvar do nového umístění v kolekci tvarů.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový cílový index, kam bude tvar umístěn. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) k přesunu v kolekci. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) metoda

Přesune zadané tvary v kolekci tvarů, umístí je počínaje zadaným indexem.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový cílový index, kam bude umístěn první zadaný tvar; následné tvary budou následovat v uvedeném pořadí. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Jedna nebo více [IShape](../../ishape/) instancí k přesunu v kolekci. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [IShape](../../ishape/)
* Třída [ShapeCollection](../)
* jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)