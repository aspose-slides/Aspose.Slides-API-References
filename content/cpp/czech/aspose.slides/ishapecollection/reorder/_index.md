---
title: Reorder()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Přesune zadaný tvar na novou pozici v kolekci tvarů.
type: docs
weight: 300
url: /cs/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) metoda

Přesune zadaný tvar na novou pozici v kolekci tvarů.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový cílový index, kam bude tvar umístěn. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) k přesunu v kolekci. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) metoda

Přesune zadané tvary v kolekci tvarů a umístí je počínaje zadaným indexem.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový cílový index, kam bude umístěn první určený tvar; následné tvary budou následovat v zadaném pořadí. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Jeden nebo více [IShape](../../ishape/) k přesunu v kolekci. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [IShape](../../ishape/)
* Třída [IShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)