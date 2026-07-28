---
title: InsertClone()
second_title: Aspose.Slides C++ API Referencia
description: Létrehoz egy másolatot a megadott alakzatról, és beilleszti azt az alakzatgyűjteménybe a megadott indexnél.
type: docs
weight: 560
url: /hu/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) metódus

Létrehoz egy másolatot a megadott alakzatról, és beszúrja azt az alakzatgyűjteménybe a megadott indexnél.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Argumentumok

| Parameter | Type | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nullától induló index, ahol a klónozott alakzatot be kell szúrni. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A [IShape](../../ishape/) a klónozandó. |
| x | **float** | A klónozott alakzat keretének x-koordinátája pontban. |
| y | **float** | A klónozott alakzat keretének y-koordinátája pontban. |
| width | **float** | A klónozott alakzat keretének szélessége pontban. |
| height | **float** | A klónozott alakzat keretének magassága pontban. |

### Visszatérési érték

Az újonnan létrehozott [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) metódus

Létrehoz egy másolatot a megadott alakzatról, és beszúrja azt az alakzatgyűjteménybe a megadott indexnél. Az új alakzat megtartja a *sourceShape* szélességét és magasságát.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Argumentumok

| Parameter | Type | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nullától induló index, ahol a klónozott alakzatot be kell szúrni. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A [IShape](../../ishape/) a klónozandó. |
| x | **float** | A klónozott alakzat keretének x-koordinátája pontban. |
| y | **float** | A klónozott alakzat keretének y-koordinátája pontban. |

### Visszatérési érték

Az újonnan létrehozott [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) metódus

Létrehoz egy másolatot a megadott alakzatról, és beszúrja azt az alakzatgyűjteménybe a megadott indexnél. A klónozott alakzat megtartja az eredeti helyzetét és méretét.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### Argumentumok

| Parameter | Type | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nullától induló index, ahol a klónozott alakzatot be kell szúrni. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A [IShape](../../ishape/) a klónozandó. |

### Visszatérési érték

Az újonnan létrehozott [IShape](../../ishape/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IShape](../../ishape/)
* Osztály [ShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)